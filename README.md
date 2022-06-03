# School_District_Analysis

## Overview

### The purpose of this analysis is to investigate the performance of a number of schools, based on standardized test results, in order for the school board to make decisions about budget allotments. 

### At one school in particular, Thomas High School, there is evidence of academic dishonesty. The reading and mathematics scores for 9th graders from the school have seemingly been altered. The altered scores must be replaced by NaNs before conducting analysis. We must then compare the results of this new analysis with the results of the original analysis before evidence of academic dishonesty was discovered.

## Results

### • In the district summary, the overall results do not change a great deal. We can see that the "Average Reading Score" remains unaffected and the other metrics           drop by only a few tenths of a percentage point in the new analysis.

## Original 
![279313791_1111900262869033_2662659917610162275_n](https://user-images.githubusercontent.com/104467100/171760649-010dfaf9-3dcb-4e32-b843-f5d7865585a1.png)

## New
![280638649_1374644979679371_3583466804834352510_n](https://user-images.githubusercontent.com/104467100/171760698-87636da7-21b9-45eb-8e2a-b114ccff2ba7.png)


### • In the school summary, the averages and percentages decrease slightly in the new analysis for Thomas High School. The averages decrease by a few hundredths and         the percentages decrease by a few tenths of a percentage point.

## Original
![281150381_270879578535964_8047340321368892506_n](https://user-images.githubusercontent.com/104467100/171761574-62e31a73-178d-4029-827c-442e2f2e1c31.png)

## New
![281143071_515633410352927_2262263554867976080_n](https://user-images.githubusercontent.com/104467100/171761630-45a39f53-c083-4789-bd19-b797b0aaaa36.png)

### • Despite the replacement of the 9th grader scores, the school overall retains its standing relative to other schools.

### • Replacing the 9th grade scores simply changes the 9th grade scores in the "scores by grade" with NaN. The scores by school spending decrease slightly after the         replacement, however the "Average Reading Score" slightly increases (this is in the $631-645 range):

## Original
![282285045_2895132844117964_8626652902898088361_n](https://user-images.githubusercontent.com/104467100/171763381-c88fb65f-b24b-4d9b-8b2e-e3ae326e3b82.png)

## New
![284473580_546985923695935_4311460653468882683_n](https://user-images.githubusercontent.com/104467100/171763403-c1bec387-7b66-4dbd-b5ea-4ee2f0b10539.png)

### • Looking at "scores by size", we can see that every metric decreases in the medium sized school category, which Thomas High School falls under:

![282234569_904154210985921_1232443190058753741_n](https://user-images.githubusercontent.com/104467100/171765030-f573c120-2e63-4f87-a90f-46519d0c4b28.png)

![279038690_2883194445315916_7130377056267578456_n](https://user-images.githubusercontent.com/104467100/171766895-6d6acdd9-08b8-463d-9ab1-a26ed7201fc1.png)

### • If we look at "scores by type", we can see that again we have an overall decrease across all metrics for charter schools in the updated analysis. However, we do       see a slight increase in "Average Reading Score":

## Original
![279235819_7472466709494811_8190294557677479724_n](https://user-images.githubusercontent.com/104467100/171768666-78083932-c292-4151-90f1-adffddaff11b.png)

## New
![282317472_429742388994541_7874724563773557194_n](https://user-images.githubusercontent.com/104467100/171768718-9dbae9a9-6e8a-44fb-9b1b-2d2fa2cc288c.png)

## Summary

### In the district summary, we see a slight decrease in all metrics except for the "Average Reading Score", which remains the same. In the school summary, we see      another slight decrease across all metrics for Thomas High School. The 9th grade score in "scores by grade" is replaced with NaN for Thomas High School. In "scores by type" we see an overall decrease in the metrics, and a slight increase in "Average Reading Score" for charter schools.
