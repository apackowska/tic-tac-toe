# tic-tac-toe

from graphics import *

def main():
    # create a default 200x200 window
    win = GraphWin("Tic-Tac-Toe")

    win.setCoords(0.0,0.0, 3.0, 3.0)

    # draw vertical lines
    Line(Point(1,0), Point(1,3)).draw(win)
    Line(Point(2,0), Point(2,3)).draw(win)

    # draw horizonal lines
    Line(Point(0,1), Point(3,1)).draw(win)
    Line(Point(0,2), Point(3,2)).draw(win)

    input("Press ENTER to continue")
    win.close()

main()
