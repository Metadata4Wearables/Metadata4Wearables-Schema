# Event Schema

```txt
https://github.com/cdsig/CDSIG-Schema/blob/main/event.json
```

Event definition in the context of actigraphy

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [event.schema.json](../out/event.schema.json "open original schema") |

## Event Type

`object` ([Event](event.md))

# Event Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                            |
| :---------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------ |
| [event_id](#event_id)               | `number` | Required | cannot be null | [Event](event-properties-event_id.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/event_id")               |
| [event_name](#event_name)           | `string` | Required | cannot be null | [Event](event-properties-event_name.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/event_name")           |
| [start_date_time](#start_date_time) | `string` | Required | cannot be null | [Event](event-properties-start_date_time.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/start_date_time") |
| [stop_date_time](#stop_date_time)   | `string` | Required | cannot be null | [Event](event-properties-stop_date_time.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/stop_date_time")   |
| [comment](#comment)                 | `string` | Optional | cannot be null | [Event](event-properties-comment.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/comment")                 |

## event_id

The unique identifier for an event

`event_id`

*   is required

*   Type: `number`

*   cannot be null

*   defined in: [Event](event-properties-event_id.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/event_id")

### event_id Type

`number`

### event_id Constraints

**multiple of**: the value of this number must be a multiple of: `1`

**minimum**: the value of this number must greater than or equal to: `0`

## event_name

Name of the event

`event_name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Event](event-properties-event_name.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/event_name")

### event_name Type

`string`

## start_date_time

Start date-time for an event

`start_date_time`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Event](event-properties-start_date_time.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/start_date_time")

### start_date_time Type

`string`

### start_date_time Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## stop_date_time

Stop date-time for an event

`stop_date_time`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Event](event-properties-stop_date_time.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/stop_date_time")

### stop_date_time Type

`string`

### stop_date_time Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## comment

Comment about an event

`comment`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Event](event-properties-comment.md "https://github.com/cdsig/CDSIG-Schema/blob/main/event.json#/properties/comment")

### comment Type

`string`
