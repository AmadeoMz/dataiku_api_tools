# dataiku_api_tools
This repository contains some useful tools using Dataiku Python API.

-Extract last run duration massively: takes the project name, extract all ids from the contained scenarios and prints the last run duration from each if they succeeded, or "failed" otherwise.

-Turning on (off) triggers massively: takes the project name, extract all ids from the contained scenarios, filters by hour and turns on/off the triggers for those scenarios scheduled in that hour.
