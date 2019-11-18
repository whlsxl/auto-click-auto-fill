# Batch

![Batch](../assets/img/batch.png)

Batch is group of action [Action](action.md) which can be Repeated with Interval. It consist of 4 parts 

- [Batch](#batch)
  - [Start Time](#start-time)
    - [Example](#example)
  - [Init Wait](#init-wait)
    - [Example](#example-1)
  - [Repeat & Repeat Interval](#repeat--repeat-interval)
    - [Example](#example-2)

---

## Start Time
You can set the start time for an extension when it need to start so you dont miss your important task to be missed out when you are busy with your other important work. It should be provided in 24 hours format `hh:mm:ss`. This is developed as per user need. It can be left 'blank'.

### Example
* `13:00:00` at afternoon 1 PM
* `00:00:00` at midnight 12 AM
* `15:15:15` at afternoon 3 PM and 15 mins and 15 seconds
*  `empty` | `blank` start immediately

---

## Init Wait
Init Wait stands for Initial Wait. Initial Wait to start particular batch/action. Waiting time is provided in `sec`. It can be used were extension need to wait few more sec for page to load fully before starting its process.

### Example
- positive numeric value `1` to `999`

---

## Repeat & Repeat Interval
If you want specific `action` to repeat more than once you can provide `repeat` value. 
If you want to control the time between each repeat you can provide `repeat Interval` as well.

### Example

**Repeat**
- positive numeric value `1` to `999`

**Repeat Interval**
* `1`
* `1.5`
* `0.5`
* `2`
* `1e4` (Random value between 1 to 4)
* `empty` | `blank`