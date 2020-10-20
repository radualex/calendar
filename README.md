# date-picker-vue3

### Description
Simple date picker created with Vue 3.

### Features:
* Select two dates (range)

### How to use it
```
npm install date-picker-vue3
```
The date picker exposes 2 events to which you can subscribe: 
* ``` first-date($event) ```
* ``` second-date($event) ```

The ``` $event ``` returns the following model: 
```
day: number
dayOfWeek: number
month: number 
year: number
momentDate: MomentDate
```

### Code example
```
import DatePicker from "date-picker-vue3";

<DatePicker
    @first-date="handleFirstDatePicked($event)"
    @second-date="handleSecondDatePicked($event)"
/>
```

### @Follow me on Twitter
[![image](https://gist.githubusercontent.com/radualex/51de7bfd86b262fec6509eecdafa5a90/raw/3b837e609b3cc263d396cbd78bedab38f930a509/icons8-twitter.svg)](https://www.twitter.com/Al_Radu)
