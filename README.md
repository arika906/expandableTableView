# expandable Table View

```diff

### Environment setup

- text in red
+ text in green
! text in orange
# text in gray

+ Open an xcode project.
+ Take a table view controller in the main storyboard.
+ Take a table view cell in the table view controller. 
+ Take UIview controller in the table view cell with a label in it besides take an image view under UIview in the table view cell.
! Set alignment.
+ Create a new file 'cocoaTouchPad' as UItableViewController
+ In main view controller, define the class
+ Connect delegate and dataSource
- Make a gap of 5 unit over the image otherwise it will create problem while using the app
- In the imgArray, set the name of the image by which it is saved in your device.
- In the nameArray, set the name you wanna show in your app.
# 'selectedIndex' is -1 because at the starting point none of the index will be selected.

# tblData.reloadData() is used for reload the data everytime.

```
**Image Assets:**

![GitHub Logo](/images/Burger.png)

