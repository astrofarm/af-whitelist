<p align="center">
  <img width="550" src="https://raw.githubusercontent.com/astrofarm/whitelist/master/images/AF_logo.jpg">
</p>
<p align="center">
  <img width="550" src="https://raw.githubusercontent.com/astrofarm/whitelist/master/images/logo.png">
</p>

* * *
         
### Main features:
       
- The entire repo is curated.
- New domains are manually added.
- Comes with a shell script i.e you can add all domains automatically at an instant.
- Domains are categorised and are included in 3 different files.
- If you are a beginner to Pi-Hole, adding these sites resolves many problems. 
       
***
     
### Description
       
The repository has 3 different files containing different domains.      
       
***whitelist.txt***       
This file contain domains that are safe to whitelist i.e it does not contain any tracking or advertising sites. Adding this file fixes many problems like YouTube watch history, videos on news sites and so on...
        
***referral-sites.txt***      
Not currently used.
           
***optional-list.txt***       
Not currently used.
          
***
           
### Installation and Usage
         
***For whitelist.txt***     
```
git clone https://github.com/astrofarm/af-whitelist.git
cd af-whitelist/scripts
sudo chmod +x whitelist.sh
sudo ./whitelist.sh
```
             
***For referral-sites.txt***          
```
git clone https://github.com/astrofarm/af-whitelist.git
cd af-whitelist/scripts
sudo chmod +x referral.sh
sudo ./referral.sh
```

**Note: You don't have to clone the repo every time you need to update whitelist file. Navigate to `whitelist/scripts` and run it again `sudo ./referral.sh`**
        
***For optional-list.txt***     
You can add it manually depending upon the service you use. 
          
***     
               

        
### Licence
```
MIT License

Copyright (c) 2018 Anudeep ND <anudeep@protonmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
