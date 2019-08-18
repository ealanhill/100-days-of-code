# 100 Days Of Code - Log

### Day 1: June 19, Wednesday

**Today's Progress**:
Determined that layout for the home screen of the app, I'm going to be using a (`MotionLayout`)[https://developer.android.com/reference/android/support/constraint/motion/MotionLayout.html] to replicate the actionbar collapse you see with a `CoordinatorLayout`. Set up databinding and the layouts for the items in the homescreens `RecyclerView`.

**Thoughts**
Well, it's a bit hard to focus on just coding for an hour. I feel like I've fallen out of practice for the past couple weeks.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/f570203f9e61df1994a127a07190a555c6c8abe3

### Day 2: June 20, Thursday

**Today's Progress**:
Completed setting up the adapter, item skeletons, and the ViewHolder skeletons for the Statistics Screen `RecyclerView`.

**Thoughts**
I chose a `ListAdapter` so that I don't have to implement a complex `DiffUtil`. Almost didn't the second day done 😅

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/e8b3d8a496d9bc0663045c48d448d450407a4a26

### Day 3: June 21, Friday

**Today's Progress**:
Set up MVVM for the spark item in my home screens `RecyclerView`.

**Thoughts**
I wanted to use/learn MVI with this project, but it definitely is going to require a bunch of research. I'm going to look at that this weekend.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/1d4145e0ce24338b9cec1f7ed63a7a1891bf688a

### Day 4: June 22, Saturday

**Today's Progress**:
Set up Koin to be able to inject the repository into any necessary components and got rid of ViewModel for the SparkItem, it was not adding anything to the architecture.

**Thoughts**
Koin was super easy to set-up. Holy cow, sooooooo much faster than Dagger

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/3f6711332f6b2ad3996eeef81b4dbfadda40d786

### Day 5: June 23, Sunday

**Today's Progress**:
* create the new statistic fragment to show the user's statistics
* convert the main activity to a databinding view
* set up the ViewModel for the StatisticsFragment so it can deliver
   some dummy data to the statistics fragment for testing

**Thoughts**
Ok, got some dummy data set up for testing. I need to figure out a better way to do this on the weekend, instead of waiting until late at night.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/a44e408792c83d5e89fa4fd7e087f12a1c369ddb

### Day 6: June 24, Monday

**Today's Progress**:
Had to correct some issues with the dummy data for the spark line. Got the entry card designed and created. And added in the beginning of the tests for the StatisticsViewModel

**Thoughts**
Things are moving along, it's a little bit each day, but defnitely starting to see progress.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/3dec1e4c9e0991d3c91332611b7348bac4a981db


### Day 7: June 25, Tuesday

**Today's Progress**:
Set up the Hour cards on the statistics screen.

**Thoughts**
I'm definitely not a designer, but I'm hoping that keeping things simple will work well.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/0141b3c73ecb93a551f21db50f84582df09549d2

### Day 8: June 26, Wednesday

**Today's Progress**
Set up MotionLayout to be able to show users a nice transition as they scroll through their statistics feed.

**Thoughts**
It's great working with something new from Google, but the lack of articles for how to use `MotionLayout` makes it hard. 🤷‍♂️

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/bbcf4951b3d8704e3ae8a92b06182d292a282804


### Day 9: June 27, Thursday

**Today's Progress**
Created the layout and basic ViewModel for the form entry.

**Thoughts**
Well, kinda got on a roll, but needed to stop to get to work on other things.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/dea7a039e9fbe1f6bd19cd1b5212c4dc75c5ff54


### Day 10: June 28, Friday

**Today's Progress**
Completed the view model for the form entry. Got some validation in for the form and saving data to the database. Still need to write the tests for the ViewModel...tomorrow's work!

**Thoughts**
Databinding can be a real pain, it definitely does not produce easy to read errors.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/df61f73c064b847f1ca943991ef05bde8087aec4


### Day 11: June 29, Saturday

**Today's Progress**
Wrote all the tests for the `EntryFormViewModel`.

**Thoughts**
Feel pretty awesome having been able to write all the automated tests for the view model.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/a396478cab55e3021e37f0cf387e65e34c3fa5fa


### Day 12: June 30, Sunday

**Today's Progress**
Hooked-up the entry form view to a `DialogFragment`. Got some data entered into the database!

**Thoughts**
Have a small issue with the keyboard, will need to work on that tomorrow.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/547e41b44c21d90630f999c7c9d3c185a5ca4ad3


### Day 13: July 1, Monday

**Today's Progress**
Swapped to using a `BottomSheetDialogFragment` and using chips for the form entry.

**Thoughts**
It's great when you get some good inspiration, but the new work is always annoying 😅

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/8a7e8fa9897d2f1fa024d0e6946636e286d75dd0

### Day 15: July 3, Wednesday

**Today's Progress**
Completed styling the bottom sheet and the chips for the user to select their levels.

**Thoughts**
Missed yesterday, but I'm good, it's allowed in the rules 😅

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/00c407e6e1d641f4f27fda85a3ffe6113eb92e26

### Day 16: July 4, Thursday

**Today's Progress**
Added a binding adapter to allow me to use databinding for the `ChipGroup`s

**Thoughts**
Having an issue compiling it, but I will need to look at that later.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/a8cf245a92a1cb8fd628006ec2f5b31a691c6c33

### Day 17: July 5, Friday

**Today's Progress**
Figured out the new databinding adapters for the `ChipGroup` (though there might be a better way to do it). Added in an error field since the `ChipGroup` doesn't have one.

**Thoughts**
I think I should create a custom `ChipGroup` that shows an error

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/79143c386abd53b84e00e483fd570751a05a65ae

### Day 18: July 6, Saturday

**Today's Progress**
Went through and corrected issues with the `EntryFormViewModel`. Started planning out the ViewModel for the Statistics screen.

**Thoughts**
Sometimes, it's not about coding, it's about planning your work.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/32c532dc3070be9a23468ff387155fb0ab312df7

### Day 19: July 7, Sunday

**Today's Progress**
Well, went through and corrected several logic errors that did not enable the submit button properly. Also updated the color of the submit button. Entry from done.

**Thoughts**
Well, I really need to make sure I plan out the next steps ahead of time so I'm not wasting a lot of time.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/88893078d20e4ed0544388b222c255ce7ae1e3d5

### Day 20: July 8, Monday

**Today's Progress**
Made some minor architecture changes to the way the main `RecyclerView` on the Statistics screen pulls data from the database. Mainly by having the item(s) pull the needed data.

**Thoughts**
I like being flexible with my architecture. I'm generally following MVVM at this point, but within that, I'm making changes as I need to, trying to keep things simple and testable.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/6a3366e6dc22d7ead776ac288a3ed3c1954caf59

### Day 21: June 9, Tuesday

**Today's Progress**
Corrected some issues when pulling the current day's entries from the database.

**Thoughts**
Need to set up some tests to be sure things are correct.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/2001b31ed6c22f94942e2546f12a8cf4250b2c98

### Day 22: July 10, Wednesday

**Today's Progress**
Properly calculated the X/Y coordinates of the points on the spark graph.

**Thoughts**
I feel better about this, but I do need to write up some tests...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/15a81e5e834892b537ca0a3be656cb494c0217ba

### Day 23: July 11, Thursday

**Today's Progress**
Well, pulled the hour entries from the database and got them displaying nicely.

**Thoughts**
Room + LiveData are awesome, I really wish I had used this before.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/42d09087937d448455fc8414624d9985375a6347

### Day 24: July 12, Friday

**Today's Progress**
Finally added some tests around the `SparkViewModel`!

**Thoughts**
Feeling good about the testing

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/1ea5ed6557fbf504a57f03d9de7ebc50d5f23406


### Day 25: July 13, Saturday

**Today's Progress**
Created the tests for the `StatisticsViewModel`

**Thoughts**
Yay for more tests!

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/52f899206d9fe419f66fa5bf944e3e2a3bb6c0ed

### Day 26: July 14, Sunday

**Today's Progress**
Correct several UI issues with the bottoms navigation bar, added in a placeholder for when there are no hour entries, and show the date at the top of the Statistics Screen

**Thoughts**
Getting to be done with the statistics screen. I'll need to spend some time over the next couple days deciding what needs to be worked on next...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/b8d1e13e44f9705fb3fe0a2ffd3c4299e0fda5de

### Day 28: July 16, Tuesday

**Today's Progress**
Started the Info screen by creating the skeleton items for the screen.

**Thoughts**
Working on implementing some of the Effective Java items...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/ed9411a646613962450854172eb16d5ac12e0545

### Day 29: July 17, Wednesday

**Today's Progress**
Created all the layouts for the info screen's views.

**Thoughts**
I like have the layouts completed, it makes things easier moving forward.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/4667bbb05320383c513eabe238ba4d75f6748826

### Day 30: July 18, Thursday

**Today's Progress**
Created the list adapter for the info screen.

**Thoughts**
I'm curious if there's a simple way to create a generic list adapter that does all this. Doubtful, it would need to be simple.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/593d767353cdb2d3d06f7cc3fdab22c98f3327a2

### Day 31: July 19, Friday

**Today's Progress**
Set up the new info fragment to display a skeleton for the info screen.

**Thoughts**
I'm curious about how to grab the metadata of a webpage 🤔

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/79bb370497c3893da179e444d193b68d2f1829b1

### Day 32: July 20, Saturday

**Today's Progress**
Planned out how I'm going to grab website metadata to be able to display it to the user in the app.

**Thoughts**
There needs to be a better way to scrap HTML tags in OkHttp than JSoup...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/56919fe81a294352e45061159c72a0f52f1651f6

### Day 33: July 21, Sunday

**Today's Progress**
Took some time to set up the network coroutines.

**Thoughts**
I'm using coroutines to learn something different. I'm familiar with RxJava that it would take no time, but I really want to stretch myself.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/84373e0f572d2985745230455f65610258737e5a

### Day 34: July 22, Monday

**Today's Progress**
Extract the metadata information from the HTML of the article.

**Thoughts**
Regex's are not an easy thing to create.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/1f5093e61d07128f9d63b125313a6e4ffd5e4b80

### Day 35: July 23, Thursday

**Today's Progress**
Loaded the metadata for articles into their respective cards.

**Thoughts**
It's nice to see my hardwork starting to pay off.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/5b7513042517c88d358ebf57e7f6b6d3c9fcaf1c


### Day 36: July 29, Monday

**Today's Progress**
Updated some UI issues with the info screen.

**Thoughts**
Took a couple days off due to a life change. But getting back into this.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/0ecc86aea69e78f3776c487d82830a33ac375614

### Day 37: July 30, Tuesday

**Today's Progress**
Added in some placeholders for the articles so it doesn't look weird while pulling the data for users.

**Thoughts**
Thinking about using facebook's shimmer library to make the placeholders more lively...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/8f0193b0396c8bba8b1c6676394f24d25ad4d65e


### Day 38: July 31, Wednesday

**Today's Progress**
Added in tests for `ArticleViewModel`, updated Mockito version, and added the mockito extensions from nhaarman.

**Thoughts**
It took some time to get the callback test working, but now it's working like a champ!

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/3e26c93f723407e8548ca26cffdd9faf9cc419e5


### Day 39: August 1, Thursday

**Today's Progress**
Some minor stuff, really. Just set up the Network module so I can test it using JUnit 5 and corrected some dependency injection issues with the Network class.

**Thoughts**
Sooooo much better to use dependency injection instead of creating classes locally.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/f701479089a7ea754f1ad6e8bd54d47e54ce068b


### Day 40: August 2, Friday

**Today's Progress**
Added a simple network test.

**Thoughts**
I'm not sure I like all the mocking I need to do to test the requests.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/af6b86a383162904601beafa5daabc710a743bd1

### Day 41: August 4, Sunday

**Today's Progress**
Finished writing the tests for the Network object.

**Thoughts**
I should pull the HTML out into a file...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/5a5789876a283922785fd8c972bcb220514e44d9


### Day 42: August 5, Monday

**Today's Progress**
Set up the repository pattern so I can cache network responses

**Thoughts**
I'm having difficulty with coroutines, I may end up switching over to Rx...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/fa13f7db95e3400c06de5ff6ab85f0cd24bf5f34


### Day 43: August 6, Tuesday

**Today's Progress**
Corrected some issues with querying the database on the main thread.

**Thoughts**
Should've done this yesterday...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/8df6861fd7aa0aa44ed9be83ffe27ab8a5cff0da

### Day 44: Aug 7, Wednesday

**Today's Progress**
Added in the tests for the repository layer of the app.

**Thoughts**
Unit testing is great, it definitely forces me to reevaluate how I'm doing something.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/9440561cd2cb3d29c64b19688912f03dd194485c


### Day 45: Aug 8, Thursday

**Today's Progress**
Created a simple WebView activity so users can read articles within the app.

**Thoughts**
It's really important that I don't take users outside of the app, it keeps engagement high.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/234b69f94ff792afb80cabf6760904f32b9422b4


### Day 46: Aug 9, Friday

**Today's Progress**
Made several corrections to ensure the web view is able to display a website. No real reason for MVVM for this activity.

**Thoughts**
You don't always need to follow the architecture strictly.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/04db8c1ec817ec27c9154b1f2ea547a6a1dd5612

### Day 47: Aug 10, Saturday

**Today's Progress**
Implemented Chrome Custom Tabs to provide a much better experience to users.

**Thoughts**
I finally figured out what I needed to do to show a proper browser in my app instead of using a WebView...woot!

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/d4aa4956cab4f5b9bf4e53a2abc751c20163e42e


### Day 48: Aug 11, Sunday

**Today's Progress**
Started the Account screen!

**Thoughts**
I'm thinking I could just use the same layout for each of the screens...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/f0f8cff11a3a5e026a1d847180a6c466c0df7594

### Day 49: Aug 12, Monday

**Today's Progress**
Set up the productivity cards for the user's account screen.

**Thoughts**
I like the way this is turning out.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/d9db28c9de9dcfd0b141142c6d468385eb9cad74


### Day 50: Aug 13, Tuesday

**Today's Progress**
Spent some time thinking on how to determine user's most productive hour of the day. Then set up the layout for the settings card on the account screen.

**Thoughts**
Creating your own algorithm is hard.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/c3b152233d6abd17d584c5b20b405b5058659b9d


### Day 51: Aug 14, Wednesday

**Today's Progress**
Well, set up a settings table in the database and pulling it from the database.

**Thoughts**
With room it's pretty easy to add new tables.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/7997df9ee16b9cca035ecbc304fd1611d9b4a138

### Day 52: Aug 15, Thursday

**Today's Progress**
Added in some tests for the Account package.

**Thoughts**
Tests, tests, and more tests

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/457aaf1a124c73adde30484e2a1b9c979ff7772b

### Day 53: Aug 16, Friday

**Today's Progress**
Finished tests for the SettingsViewModel

**Thoughts**
Having tests, definitely makes me feel comfortable with business logic.

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/5217cc1f37df1058792ae73bd3f1e89b58c24b36

### Day 54: Aug 18, Sunday

**Today's Progress**
Got the adapter set up to show the user's their account information

**Thoughts**
Sometimes, I think I write too much boilerplate...

**Link(s) to work**
https://github.com/ealanhill/bpt/commit/581bc3cff7a12d37ce12d41d6be1490e9759d952
<!--
### Day : June 26, Wednesday

**Today's Progress**


**Thoughts**


**Link(s) to work**

-->
