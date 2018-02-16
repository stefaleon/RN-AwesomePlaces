[React Native - The Practical Guide](https://www.udemy.com/react-native-the-practical-guide/) by [Maximilian Schwarzmüller](https://www.udemy.com/user/maximilian-schwarzmuller/)

* Start with CRNA
```
npm install -g create-react-native-app
```
```
create-react-native-app AwesomeProjectCRNA
```
```
npm run eject
```


&nbsp;
## TextInput

* Add a textInput for the *placeName* and the code for its functionality (initialize state, create handler, style it).



&nbsp;
## Button

* Add a button and configure it. Contain it in another view along with the textInput.

* Add the handler for the submit event.

* Output the stored *places* in another view.



&nbsp;
## ListItem

* Add the *src* folder and the *ListItem* component.



&nbsp;
## Refactor to components

* Refactor the components to the *PlaceList* and *PlaceInput* files in the *src* folder.



&nbsp;
## Listening to Touch Events

* Wrap the *places* items inside *TouchableXXXX* wrapper components in order to react to touch events.



&nbsp;
## Reacting to Press Events

* Pass the clicked item's index from the *PlaceList* to the *placeDeletedHandler* in the App container using the *onItemDeleted* property.



&nbsp;
## ScrollView

* In the *PlaceList* return a *ScrollView* instead of a simple view.


&nbsp;
## Rendering Lists Correctly

* Use the *FlatList* component to ensure performance for long dynamic lists. Refactor the *placeAddedHandler* so that the places array is filled with key-value objects instead of plain strings, in order to provide appropriate keys to the data. Adjust *placeDeletedHandler* accordingly. 
