# UIScrollView

While we are using UIScrollView that stuck for the managing constrain. So here is the dam easy way to manage UIScrollView by AutoLayout.


Steps:

1 Take a UIScrollView.

2 Set Constrain as trailing, leading, top and bottom with 0.

3 Take a UIView for manage UIScrollView.

4 Set Constrain as trailing, leading, top and bottom with 0.

5 Now We can see AutoLayout issue so additionally, We add 2 more constrain to UIView like Equal Width to SuperView and Equal Height give same as you want.(I am giving here 1900 for testing)

6.Run the app and test it.

You can see it:

https://youtu.be/ru4v46Lg3bY

Medium:
https://medium.com/@javedmultani16/uiscrollview-configure-using-autolayout-84e9ed1205ec

![screen shot 2018-06-25 at 1 00 45 pm](https://user-images.githubusercontent.com/16849127/41836362-16970838-7878-11e8-8062-1aa23dd6ece1.png)
