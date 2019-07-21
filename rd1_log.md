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
<!--
### Day : June 26, Wednesday

**Today's Progress**


**Thoughts**


**Link(s) to work**

-->
