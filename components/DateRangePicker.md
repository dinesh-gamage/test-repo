# DateRangePicker






This component is used to select a date range.



## Installation



```tsx
import {DateRangePicker} from 'uxp/components';
```

## Examples



```tsx
<DateRangePicker
     startDate={startDate}
     endDate={endDate}
     closeOnSelect
     onChange={(newStart, newEnd) => { setStartDate(newStart); setEndDate(newEnd) }}
 />
```

## Properties

|Name|Type|Description|
|-|-|-|
|title|string||
|startDate|string \| Date|start date of the range. Either a Date object or an ISO8601 string representation of a date |
|endDate|string \| Date|end date of the range. Either a Date object or an ISO8601 string representation of a date |
|onChange|(newStartDate: Date, newEndDate: Date) => void|Callback that gets executed whenever a date range is selected/changed in the date picker |
|closeOnSelect|boolean|Called when the calendar popup is closed |
|disableInput|boolean|Set to true to prevent a user from typing in a date |
|options|{ /** * The minimum selectable date. Either a Date object an an ISO8601 date string */ minDate?: string \| Date, /** * The maximum selectable date. Either a Date object an an ISO8601 date string */ maxDate?: string \| Date, /** * If set to `true`, you cannot select a weekend date */ disableWeekEnds?: boolean, /** * An array of specific dates that the user cannot select */ disableDates?: Array<Date \| String> }|Additional options to control behavior |
### title



---





|type|
|-|
|string|
### startDate



---



start date of the range. Either a Date object or an ISO8601 string representation of a date


|type|
|-|
|string \| Date|
### endDate



---



end date of the range. Either a Date object or an ISO8601 string representation of a date


|type|
|-|
|string \| Date|
### onChange



---



Callback that gets executed whenever a date range is selected/changed in the date picker


|type|
|-|
|(newStartDate: Date, newEndDate: Date) => void|
### closeOnSelect



---



Called when the calendar popup is closed


|type|
|-|
|boolean|
### disableInput



---



Set to true to prevent a user from typing in a date


|type|
|-|
|boolean|
### options



---



Additional options to control behavior


|type|
|-|
|{ /** * The minimum selectable date. Either a Date object an an ISO8601 date string */ minDate?: string \| Date, /** * The maximum selectable date. Either a Date object an an ISO8601 date string */ maxDate?: string \| Date, /** * If set to `true`, you cannot select a weekend date */ disableWeekEnds?: boolean, /** * An array of specific dates that the user cannot select */ disableDates?: Array<Date \| String> }|
