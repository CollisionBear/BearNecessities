# Bear Necessities
![alt Bear Data editor splash](https://repository-images.githubusercontent.com/609868413/f422bb44-c553-4368-a2b4-95aa2fa48dca)
 List, Search, and edit objects with an easy-to-access alternative to the Project view. Working with Bear Data Editor enables frictionless editing of your content from a single place as your project grows.

Any Class inheriting from ScriptableObject and MonoBehaviour can use the [BearDataEditor] attribute (available in the CollisionBear.BearDataEditor namespace)to be exposed by the editor window.
The editor can display any scriptable objects, or prefab with a monobehavior component, of a given type. The editor finds them in the project folder regardless of location and sorts the results by name. 
Support for several open editor instances simultaneously is also available, along with filtering among the objects based on their names.

Next to every asset is a folder icon that reveals its location in the Unity project folder. 

## Getting started
First you need to get your hands on a copy of the package. We support a few options. 

### Unity Package
The editor extension can be added Unity's package manager from 'Add package from git URL'
* <https://github.com/CollisionBear/BearDataEditor.git>

### Manual download
You need to put the Bear Data Editor content inside your Unity project's Asset folder.
* <https://github.com/CollisionBear/BearDataEditor/releases/download/1.0.0/BearDataEditor-1.0.0.unitypackage>

## Example
Decorate a class with the attribute. By default the class's name will be displayed.

## License
This project is released as Open Source under a [MIT license](https://opensource.org/licenses/MIT).
