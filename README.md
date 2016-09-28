CoreGraphics Links

[link 1](http://vormlab.com/coregraphics-tutorial-swift/)

[SwiftChart](https://github.com/gpbl/SwiftChart)

[Apple](https://developer.apple.com/reference/coregraphics)

[text](http://www.techotopia.com/index.php/An_iOS_8_Swift_Graphics_Tutorial_using_Core_Graphics_and_Core_Image)

CoreGraphicsGraph
=================
![Example](http://cl.ly/image/3M3y0A3w2C1F/d)
Draw a line graph with CGPath and Swift. This is really just the result of playing with Swift, and so I can't garuntee the code is production ready, or even very good.

```swift
// GraphView.swift example usage

let myData = [
    ["label" : "Mon",   "value" : NSNumber(int:15)],
    ["label" : "Tues",  "value" : NSNumber(int:30)],
    ["label" : "Weds",  "value" : NSNumber(int:7)],
    ["label" : "Thurs", "value" : NSNumber(int:60)],
    ["label" : "Fri",   "value" : NSNumber(int:30)],
    ["label" : "Sat",   "value" : NSNumber(int:15)],
    ["label" : "Sun",   "value" : NSNumber(int:45)],
] as NSArray

let graph = GraphView(frame: CGRectMake(50, 50, 420, 200), data: myData)
self.view.addSubview(graph)
```

## Graph customisation options
There isn't really that many…

  - **showLines**   - whether or not to display lines from Y axis values
  - **showPoints**  - whether or not to display points on the line graph
  - **linesColor**  - The colour of Y axis lines if visible
  - **axisColor**   - The colour of the X and Y axis
  - **graphColor**  - The colour of the actual line graph and points
  - **labelFont**   - Axis label font
  - **labelColor**  - The colour of the axis labels


## To do
  1. ~~Add x axis label support~~
  2. ~~Build y axis labels from values~~
  3. ~~Customisation options~~
