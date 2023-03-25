# Event-level metadata (within dataset)

- [1. Property `Event-level metadata (within dataset) > event_id`](#event_id)
- [2. Property `Event-level metadata (within dataset) > event_name`](#event_name)
- [3. Property `Event-level metadata (within dataset) > start_date_time`](#start_date_time)
- [4. Property `Event-level metadata (within dataset) > stop_date_time`](#stop_date_time)
- [5. Property `Event-level metadata (within dataset) > comment`](#comment)

**Title:** Event-level metadata (within dataset)

|                           |                                                                           |
| ------------------------- | ------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                  |
| **Required**              | No                                                                        |
| **Additional properties** | [[Any type: allowed]](# "Additional Properties of any type are allowed.") |

**Description:** Event definition in the context of actigraphy or light data set

| Property                               | Pattern | Type   | Deprecated | Definition | Title/Description |
| -------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| + [event_id](#event_id )               | No      | number | No         | -          | Event ID          |
| + [event_name](#event_name )           | No      | string | No         | -          | Event name        |
| + [start_date_time](#start_date_time ) | No      | string | No         | -          | Start datetime    |
| + [stop_date_time](#stop_date_time )   | No      | string | No         | -          | Stop datetime     |
| - [comment](#comment )                 | No      | string | No         | -          | Comment           |

## <a name="event_id"></a>1. Property `Event-level metadata (within dataset) > event_id`

**Title:** Event ID

|              |          |
| ------------ | -------- |
| **Type**     | `number` |
| **Required** | Yes      |

**Description:** The unique identifier for an event

| Restrictions    |        |
| --------------- | ------ |
| **Multiple of** | 1      |
| **Minimum**     | &ge; 0 |

## <a name="event_name"></a>2. Property `Event-level metadata (within dataset) > event_name`

**Title:** Event name

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Name of the event

## <a name="start_date_time"></a>3. Property `Event-level metadata (within dataset) > start_date_time`

**Title:** Start datetime

|              |             |
| ------------ | ----------- |
| **Type**     | `string`    |
| **Required** | Yes         |
| **Format**   | `date-time` |

**Description:** Start date-time for an event

## <a name="stop_date_time"></a>4. Property `Event-level metadata (within dataset) > stop_date_time`

**Title:** Stop datetime

|              |             |
| ------------ | ----------- |
| **Type**     | `string`    |
| **Required** | Yes         |
| **Format**   | `date-time` |

**Description:** Stop date-time for an event

## <a name="comment"></a>5. Property `Event-level metadata (within dataset) > comment`

**Title:** Comment

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |

**Description:** Comment about an event

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2023-03-25 at 13:10:53 +0100
