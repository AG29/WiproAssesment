# WiproAssesment
iOS Project Assesment

Functional Description:
1.    Implemented combination of MVC and MVVM, clean architecture for implementing the base of application model.
2.    Implemented loading of 3 APIS: Album, Artist, and Track at simultaneously means asynchronously loading.
3.    UI: The App contains three segment buttons: Album, Artist, and Songs with search bar controller. There is one detail view which can provide the detail of specific tapped element.
4.    Implemented lazy loading and caching mechanism for loading images in UITableView with animated loader for nice user experience.
5.    Implemented separate Network layer and business logic layer for simplicity and to use power of MVVM architecture in right way.
6.    Implemented sample test cases for testing artists functionality.
7.    App is created in latest swift environment and tested well in instrumentation tool for zero memory leak.


App UI Details:
Once the App is launched it shows the main screen which consist of search bar, and 3 segments (Album, Artists, and Songs). Type any name or character in search bar for example
"AG" and hit search button or return button on keyboard, it will show the result in all 3 segments simultaneously.
Once tapped on any element a detail view will popped out to show the detail.
