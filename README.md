MarsPhotos
==================================

Introduction
------------

MarsPhotos is a demo app that shows actual images of Mars' surface. These images are
real-life photos from Mars captured by NASA's Mars rovers. The data is stored on a Web server
as a REST web service.  The app demonstrates the use of [Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service, [Moshi](https://github.com/square/moshi) to
handle the deserialization of the returned JSON to Kotlin data objects, and [Coil](https://coil-kt.github.io/coil/) to load images by URL.

The app also leverages [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata), and
[Data Binding](https://developer.android.com/topic/libraries/data-binding/) with binding 
adapters.


<img src="https://user-images.githubusercontent.com/8702105/165186085-5cf71808-d848-46ff-9861-a9cabb848e7c.jpg" width="300" height="600">      <img src="https://user-images.githubusercontent.com/8702105/165186087-2632050d-33f0-4991-955f-efb7976beb97.jpg" width="300" height="600">
