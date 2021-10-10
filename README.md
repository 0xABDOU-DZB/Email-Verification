# --------- Project Expired, Not working anymore ----------- #

# Automatic-Email-Verification

Building a Python module For Automatic Email Verification using Python and temp-mail.org

 ## Usage

### Simply add module to your project and

```python
import AutomaticEmailVerification as aev
```

### You can get all available domains by using 
```python
aev.getAvailableDomains() # Returns a List of Available Domains
```

### You can get a random domain by using 
```python
aev.getADomain() # Returns a string ex: @cliptik.net
```

### **Fetch an email using**
```python
aev.fetch("ABDOU_DZB@cliptik.net") 

# Returns a String in case of Error.
# or returns an array of emails each with link, subject, sender, body.

# optionally you can specify weather you want all the content or not.

aev.fetch("ABDOU_DZB@cliptik.net", body, subject, sender,link)
# each as 0|1 as per your requirement.
```

<h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/>Connect with me:</h1>
<p align="left">
<a href="https://github.com/ABD0U-DZB" target="_blank"><img height="30" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.instagram.com/abdou_dzb2/" target="_blank"><img height="30" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://twitter.com/ABDOU_DZB" target="_blank"><img height="30" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.youtube.com/channel/UCT8ED2KaMXmoSviKd7972Fw" target="_blank"><img height="30" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/youtube.svg"></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
