# SafeAreaExample

MainPage.xaml
```xml
﻿<Page x:Class="UnoApp8.MainPage"
	  xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
	  xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
	  xmlns:local="using:UnoApp8"
	  xmlns:utu="using:Uno.Toolkit.UI"
	  utu:SafeArea.Insets="Top"
	  Background="CornflowerBlue">
	<Grid>
		<TextBlock Text="Hello Uno Platform"
				   VerticalAlignment="Top"
				   HorizontalAlignment="Center" />
	</Grid>
</Page>
```

Without SafeArea|With SafeArea
-|-
![Screenshot_1708008280](https://github.com/kazo0/SafeAreaExample/assets/4793020/e0b70635-a65b-4968-b3f1-39dddc2777e0)|![Screenshot_1708008258](https://github.com/kazo0/SafeAreaExample/assets/4793020/bdc1d7e8-df01-4aab-a7d3-c36c333b7116)
