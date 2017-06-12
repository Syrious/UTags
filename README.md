UTags
=====

Plugin with helper functions for editing data stored in tags in key-value pair
form.

`TagType:Key1,Value1;Key2,Value2;Key3,Value3;`

USage
=====

-   Add the plugin to your project (e.g `MyProject/Plugins/UTags`)  
    

-   Add the module dependency to your module (Project, Plugin); In the
    `MyModule.Build.cs` file:  

		PublicDependencyModuleNames.AddRange(  
		new string[]  
		{  
		...  
		"UTags",  
		...  
		}  
		);  
    

-   Include `TagUtils.h` where you plan to use the  tag utils functions.
