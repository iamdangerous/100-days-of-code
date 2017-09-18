# 100 Days Of Code - Log

### Day 1: Sept 14, 2017


**Today's Progress**: Implemented saving of  images into android private directory, learned about Android Storage access framework, worked on functionality for the app.

**Thoughts:** I really struggled on how to store gallery image's Uri or absolute path in Sqlite db so I can use that Uri to show image anytime but I was always getting an exception of having permission of MANAGE_DOCUMENTS then I learned about new Android storage Access Framework for API>19. So now I am creating my own copy of that image in the app private directory in this way I can use that image anytime by storing its new path

**Link to work:** [Awesome Text editor](https://github.com/iamdangerous/Android-Text-Editor)    


### Day 2: Sept 16, 2017

**Today's Progress**: Read the book Kotlin for Android Developers by Antonio Leiva. Right now I am at chapter 7. Implemented Anko(kotlin library) and kotlin extension functions. Fixed the issue for showing all saved notes in my text editor app by using nested select and group queries in Android Room. Fixed minor bugs in the android app like adding of images as bitmap from database

**Thoughts:** I love the Android architecture components. Till now I have played with Room. Its speeds up the development process like by 100 times by auto generating mapping code of cusor and Data class. Knowing sql queries really makes your life easier as. I have just started with Anko library and till now I love it. In kotlin I read about how to use extension functions and how it helps to reduce your boilerplate code .I still have long way to go in kotlin.

**Link to work:** [Awesome Text editor](https://github.com/iamdangerous/Android-Text-Editor)    

### Day 3: Sept 17,2017

**Today's Progress:** I have completed chapter 8,9 and 10 of Kotlin for Android Developers by A.Leiva. Read about how replace legacy Async Task with Anko in just 3 lines of code using doAsync(){....}.
Read about a new concept of declaraion desctructing, companion objects(static in java), divide your code base into 3 layers - that is UI Layer(Activity & views), Response Layer (responses from Gson) & Domain Layer (actual classes that are used like in Recycler view).
Implemented Java executor framework which helps in create a thread pool and read about the Future and Callables in Java

**Thoughts:** Dividing the code into into Response and domain is a very nice way to make your app more debuggable and scalable. Finally created a sample app of Weather forecast and kotlin with Anko really helps to simplify the code base. Future and Callables are new for me, need to research more on that.
