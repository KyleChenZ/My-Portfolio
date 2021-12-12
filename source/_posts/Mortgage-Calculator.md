---
title: Mortgage Calculator
date: 2018-07-11 21:23:31
categories:
- Projects
- Android
tags:
- Android application
- Java
thumbnailImagePosition: left
thumbnailImage: https://lh3.googleusercontent.com/AOqlVYxNKQ6OURCtdWiMzZ-j_5alYyuGmFuaGsfMGdkLfZ7KRG5hhEQUjlJXn8GKl0KIda4ViaaVJtePKEXSL8Z5WIYOLaHbdWl0Y5WEeyuMrOR4x0qcuCvyCx2VLV1OUmdByYuIjDF8pGHWgB64pdLC5q2FDzJ3MtfEgDeiDpU8xoIDAX_GHHO_bxc3TjpwD3PS7AmFlVuhmaopmI7CXOlM6gG1wQCquv-GuoVySeUmf3VGvzyjoJFHM38QwUvQkWiDpQl2Y9bK0F9gaacuIcJhRXQ_EOJTZC0y1UV2kJ8qv0kbHFWjmLEQgt-VgRPTxr8I6xcQ-Qn-RP3n_wkp3wsT-GyDpTuxGWGwSMcimkxL2YlmZK21ESsflzfQJW0LFYKz9ypt7ZI1jwYHdyXKWNS753dWqQYZRwma94RmAhE_rnuU0Ziu-zf_1YglQHEm3RBwHn-wbIwPT3viJHpqA1jc6eOrDhBI9zHDKmf_YrtVILPYhjcjb6S6yKITdwMmnjDPPhzN7H3e4dqOTMzz8Dm-fS3LqKfCsWfmBB3o4pgqaZia6yqK36AiAIEzO3Fma4uzp1sC9knMQa_WIRvLelUltimgvOEVYnOG4j8=w1000-no-tmp.jpg
metaAlignment: left
---
Description: An Android application that allow users to do calculate their monthly payment to based on house price etc.

Github: https://github.com/KyleChenZ/Mortgage-Calculator

<!--more-->

## Keypoints:
- The view of this app can be change based on screen size and landscape/portrait mode (tested on Nexus 5 and Nexus 10)
- Two fragments are displayed in one activity
- This app has error handling for the inputs
- Scroll view for each fragment

## How to use:
- Enter information in the input section
- There are home value and down payment in U.S. dollar
- Interest Rate and Property Tax Rate in percentage (%)
- Typical Property Tax Rate in U.S should be between 0.00% to 2.00% depending on the county.
- Choose a Term (year) from the given choices (15, 20, 25, 30, 40)
- Press Calculate and check the summary on the output section
- Make sure to scroll to see all the contents for small screen devices
- Press Reset button to clean all input and output
- Error messages will be shown if some information are not provided

## Screenshots:
### Result of the input (landscape mode):
![Result of the input](https://user-images.githubusercontent.com/21185752/41812122-d0402cae-76d1-11e8-9b34-5c337f297142.PNG)

### After pressing the reset button (portrait mode):
![After pressing the reset button](https://user-images.githubusercontent.com/21185752/41812123-d0576b1c-76d1-11e8-9250-23840c15888f.PNG)

### Error handling (portrait mode):
![Error handling](https://user-images.githubusercontent.com/21185752/41812124-d06e3482-76d1-11e8-8b4b-38a8dbb5d0b0.PNG)