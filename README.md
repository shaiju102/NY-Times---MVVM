# Android MVVM Architecture: Sample App
This repository contains a detailed sample app that implements MVVM architecture using Android Archtecture components like VewModel , LiveData and Data Binding.
The app basically fetch certain news feeds and list them in a recycler view

Prerequisites
--------------

- Android Studio 3.1
- Android SDK v27
- Latest Android Build Tools
- Android Support Repository

#Technology used
* Clean MVVM architecture
* [Android Databinding](https://developer.android.com/topic/libraries/data-binding/index.html)
* [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
* [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
* [Retrofit](https://square.github.io/retrofit/)
* [Glide](https://github.com/bumptech/glide)


#### The app has following packages:
1. **model**: It contains all the data accessing and manipulating components.
2. **view**: It contans the view classes like Activitiy, Fragment.
3. **viewmodel**: It contains the view model class that acts as a hooke between the model and the view.
4. **network**: Retrofit classes .
4. **callback**: General interfaces.

License
--------


    Copyright 2017 Shaiju MS.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

