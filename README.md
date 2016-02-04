# NapySlider
A vertical slider UIControl element written in swift

## Howto
The easiest way to add a NapySlider is in the storyboard. Add a ```UIView``` element and set its custom Class to ```NapySlider```. Now you can define the inspectable properties, like min, max, step and all the colors.

### Add it programatically
Of course, you can add a slider by code.

```swift
var myNapySlider:NapySlider!

// add this lines to the viewDidLoad function, or wherever you like
myNapySlider = NapySlider(frame: yourFrame)
myNapySlider.min = 0
myNapySlider.max = 100
myNapySlider.step = 20

view.addSubview(myNapySlider)
```

