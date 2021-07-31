# Product Monitoring + Service Now Alerting - Research and Design

### Workflow Of Design

__STEP 1:__

_Login to Data dog usin [Link text Here](https://link-url-here.org)__  

__STEP 2:__

_Select the Monitors tab on the left side of the panel_

__STEP 3:__

_After that select New Monitor tab _

__STEP 4:__

_The above page will route to select monitor type, select metric as monitor type_ 

__STEP 5:__

_Now we are in main page where we need to configure the metric_
_This page contains five sections_ 
1. Choose a detection method
2. Define the metric
3. Set alert conditions
4. Say what's happening
5. Notify your team
    
#### 1. Choose detection method

* In this Choose Threshold Alert as detection method which means an alert is triggered whenever metric crosses the threshold 

#### 2. Define the metric

* This is place where we need to define the query 
* To keep as simple as possible , selected the aws.s3.5xx.errors from one of production server

#### 3. Set alert conditions

* In the alert conditions we need to set threshold condition which means if the above source events exceeds this much number then trigger this incident
* We also need to check for how many times this incident needs to be monitored like for every 5 min,10min etc

#### 4. Say what's happening

* Pls follow the below documentation   
[Documentation link shared by Tim](https://www.google.com)

#### 5. Notify your team
* This is the section where we need to add email ids to notify
* To trigger SNS syntax is @ sns-\<SNS-topic-name\>
* eg: @sns-sns.puas.topic.name, @sushmadevulapalli etc


```python

```
