# Tip Calculator 

## Bryant Jimenez

**Tippy** computes the tip and total amount for a bill. The app uses the base amount and tip percentage to calculate the amount owed, and it also describes the quality of service based on the tip.

Time spent: **5** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [X] User can enter in a bill amount (total amount to tip on)
* [X] User can enter a tip percentage (what % the user wants to tip).
* [X] The tip and total amount are updated immediately when any of the inputs changes.
* [X] The user sees a label or color update based on the tip amount. 

The following **extensions** are implemented:

* [X] Custom colors palette selected
* [X] Ability to split the bill evenly among up to 20 people

## Video Walkthrough

Here's a walkthrough of implemented user stories:

https://imgur.com/a/YxEIzxf

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

One of the challenges that I had while building this app was learning all of the structures and
items that are in Android Studio, like all of the different buttons, widgets, text options, etc.
This is my first ever app, and so it took me a while to get used to the semantics and nature of Android
Studio regarding constraints and alignments. 

Additionally, the bill-splitting extension also took me a bit of time to think through, since I had 
initially wanted to go with a different design implementation (an edit text, rather than a slider), 
but decided against it because it became to convoluted and would have needed further bug proofing 
for erroneous inputs like negative numbers or obscenely large numbers. For that reason, I chose to 
go with a simple slider for the bill-splitting functionality. 

Overall, I had a ton of fun making this app and am really proud of what I was able to accomplish for
my first ever project. Looking forward to improving in the future.

## License

    Copyright [2021] [Bryant Jimenez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
