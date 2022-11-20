# ScrollView comparisons

React Native has two main ScrollViews. 

When the content on your screen is larger than the device height, you should use `KeyboardAwareScrollView` so that your screen becomes scrollable with the keyboard up.

When you don't need to scroll through your content but don't want your content hidden behind the screen, use `KeyboardAvoidingScrollView`.