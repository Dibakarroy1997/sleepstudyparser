# Sleep Study Parser

Simple package which can be used to parse the sleep study report from Windows 11.

## Usage

```python
>>> from sleepstudyparser.SleepStudyParser import SleepStudyParser
>>> ssp = SleepStudyParser(number_of_days=2, report_name="DummySleepStudyReport", report_path=r"C:\temp")
>>> obj = ssp.parse()
>>> obj.states[0]
```