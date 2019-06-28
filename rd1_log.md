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

<!--
### Day : June 26, Wednesday

**Today's Progress**


**Thoughts**


**Link(s) to work**

-->
