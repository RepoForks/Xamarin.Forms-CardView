# Xamarin.Forms-CardView
A Package to create a CardView using Xamarin.Forms that works on the three platforms (Android, iOS, UWP)
It is simple to use in a straight forward fashion.
You may either use it in C#, or in XAML.  

## CardView Bindable Properties

| Property                              | Property Name                 | Property Type   | Usage           | Default Value   |
| :-------------:                       | :-------------:               | :-------------: | :-------------: | :-------------: |
| CardViewContentProperty               | CardViewContent               | View            | Used to add any desired content inside the CardView                        | None        |
| CardViewHeightRequestProperty         | CardViewHeightRequest         | double          | Used to give a desired height for the CardView                            | 300.0       |
| CardViewOutlineColorProperty          | CardViewOutlineColor          | Color           | Used to give the CardView an outline Color                               | Transparent |
| CardViewOutlineColorThicknessProperty | CardViewOutlineColorThickness | Thickness       | Used to give the outline Color a desired thickness                   | 0.5         |
| CardViewOutlineColorHasShadowProperty | CardViewOutlineColorHasShadow | bool            | In case you have used an outline color, decide if you want a shadow or not. | false       |

Example:  
```xml
    <StackLayout>
        <CardView CardViewHeightRequest="125" CardViewOutlineColor="Aqua" CardViewOutlineColorThickness="5">
            <CardView.CardViewContent>
                <!-- You can enter here any content you want to -->
                <StackLayout>
                    <Label Text="First Line" />
                    <Label Text="Second Line" />
                </StackLayout>
            </CardView.CardViewContent>
        </CardView>
    </StackLayout>
```
