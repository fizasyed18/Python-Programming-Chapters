# Datetime

## **Date Class**

The date class is used to create and manipulate calendar dates. A date object contains the year, month, and day.

**Syntax**\
`class datetime.date(year, month, day)`

**Parameters:**\
- **year:** Year of the date.
- **month:** Month from 1 to 12.
- **day:** Valid day for the specified month and year.

### **Date Class Methods**

| Method | Description |
|---|---|
| **today()** | Returns the current local date |
| **isoformat()** | Converts a date into YYYY-MM-DD format |
| **strftime()** | Formats a date according to a specified format |
| **fromisoformat()** | Creates a date object from an ISO-formatted string |
| **replace()** | Returns a date with selected values changed | 
| **isoweekday()** | Returns the weekday as an integer from 1 to 7 |
| **weekday()** | Returns the weekday as an integer from 0 to 6 |

## **Time Class**

The time class represents a time of day independently of a date. It can contain hour, minute, second, microsecond, and timezone information.

**Syntax**\
`time(hour=0, minute=0, second=0, microsecond=0, tzinfo=None)`

### **Time Class Methods**

| Methods | Description |
|---|---|
| **isoformat()** | Returns the time as an ISO-formatted string|
| **replace()** | Returns a time object with selected values changed|
| **strftime()** | Formats the time according to a specified format |
| **fromisoformat()** | Creates a time object from an ISO-formatted string |

## **Datetime class**

The datetime class combines date and time information in a single object. It is commonly used when both the date and time of an event need to be stored or processed.

**Syntax**\
`datetime(year, month, day, hour=0, minute=0, second=0, microsecond=0, tzinfo=None)`

**Parameters:**\
- year: Year of the date.
- month: Month from 1 to 12.
- day: Valid day for the specified month and year.
- hour: Hour from 0 to 23.
- minute: Minute from 0 to 59.
- second: Second from 0 to 59.
- microsecond: Microsecond from 0 to 999999.

### **Datetime Class Methods**

| Function Name	| Description |
|---|---|
| **now()**	| Returns the current local date and time | 
| **today()** |Returns the current local datetime | 
| **strftime()** | Converts a datetime object into a formatted string |
| **fromisoformat()** | Creates a datetime object from an ISO-formatted string |
| **timestamp()** | Returns the POSIX timestamp |
| **date()** | Returns the date part of a datetime object |
| **time()** | Returns the time part of a datetime object |
| **isoformat()** | Returns the datetime in ISO 8601 format |
| **replace()** | Returns a datetime object with selected values changed |
| **strptime()** | Creates a datetime object from a formatted string|
