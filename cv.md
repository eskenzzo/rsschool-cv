# **Yeskendir Ybyray**
**************
## Contacts
* Email   : eskenzzo@gmail.com
* Telegram: eskenzzo
* Discord : eskenzzzo#1279

**************
From the school ages I interested in math and decided to continue that path in Computer Science. After successful selection to the university I started to learn programming more deeply. Currently I am in a way of web developer with a focus on frontend. My goal is to be compteble for solid position in company after graduation. 
**************
## Education
* 2021-     : Nazarbayev university
    * Computer Science major
* 2013-2020 : Specialized lyceym for gifted children №20, Taldykorgan

**************
## Skills
* HTML
* CSS
* JavaScript
* C\C++
* Python
**************
Examples of code from [Leetcode](https://leetcode.com/problems/container-with-most-water/)
```
    class Solution {
        public:
            int maxArea(vector<int>& height) {
                int maxarea = 0;
                size_t area = 0;
                int i = 0, j = height.size() - 1;
                while (i < j) {
                    area = (j-i)*min(height[j], height[i]);
                    maxarea = area > maxarea ? area : maxarea;
                    if (height[i] < height[j]) i++;
                        else j--;
                }
                return maxarea;
            }
        };
```
**************
## Projects:
* Own website-cv
* Online-calculator
* CV in MarkDown

**************
## Languages: 
* Kazakh - native
* Russian - second language
* English - B1
