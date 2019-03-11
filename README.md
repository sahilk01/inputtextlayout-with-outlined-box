# inputtextlayout-with-outlined-box

Add Material Design Edit Text With Outlined Box Like this:

![screenshot1](https://github.com/sahilk01/inputtextlayout-with-outlined-box/blob/master/Screenshot_20190310-162407.png)


![screenshot1](https://github.com/sahilk01/inputtextlayout-with-outlined-box/blob/master/Screenshot_20190311-135513.png)



STEPS:

1. Set target and compiled SDK = 28.

2. Change theme from AppCompat to MaterialComponents in styles.xml. like this:
<style name="AppTheme" parent="Theme.AppCompat.Light.DarkActionBar"> ==> <style name="AppTheme" parent="Theme.MaterialComponents.Light.DarkActionBar">

3. add design library in Gradle: implementation 'com.android.support:design:28.0.0'

4. use <android.support.design.widget.TextInputEditText> layout under <android.support.design.widget.TextInputLayout> in Activity xml.

5. add: style="@style/Widget.MaterialComponents.TextInputLayout.OutlinedBox" in TextInputLayout.

THAT'S IT!

 CHANGING COLORS:
 
1. change the hover color by changing color accent.
 
2. change the default (unhovered) hint color by Adding: 
 
 android:textColorHint="YOUR COLOUR"
 
 in TextInputLayout
 
 3. change the default (unhovered) outline box color by "ctrl+left click" on MateialComponents theme, find and change "default box stroke color".
 
