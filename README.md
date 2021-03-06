# hCaptcha - CAPTCHA Plugin 
CAPTCHA Plugin for Joomla 3.8 and higher. 
A simple CAPTCHA Plugin using the [hCaptcha](https://www.hcaptcha.com/) CAPTCHA service 
to protect your Joomla website against SPAM.

The Plugin can be easily kept up-to-date because it uses Joomla! Update System. 

The latest version can be downloaded from: https://data2site.com/download/hcaptcha

## Instructions

- [Download the latest version of hCaptcha](https://data2site.com/download/hcaptcha) 
and install using Joomla's Extension installer
    - in the Joomla back-end: Extensions > Install
- Create a free account at [https://hcaptcha.com](https://hcaptcha.com)
- Add your site to https://hcaptcha.com and get a Secret Key + Site Key 
- Add the Secret Key + Site Key to the hCaptcha plugin 
    - in the Joomla back-end: Extensions > Plugins > Select: hCaptcha
    - add the Site Key + Secret Key
    - publish the hCaptcha Plugin
- Configure your Joomla site to use hCaptcha as default:
    - in the Joomla back-end: System > Global Configuration > [Site] tab > 
    Default Captcha > Select "Captcha - hCaptcha"
- Test your forms on the front-end of your Joomla website to see if the hCaptcha 
has been configured properly and works correctly.

## Translations
This plugin has been translated into the following languages:
- Dutch (nl-NL) by Peter Martin ([@pe7er](https://github.com/pe7er))
- French (fr-FR) by Yannick Berges ([@micker](https://github.com/micker))
- German (de-DE) by Tobias Zulauf ([@zero-24](https://github.com/zero-24))
- English (en-GB) by Peter Martin ([@pe7er](https://github.com/pe7er))
- Polish (pl-PL) by Mateusz Hajder ([@mhajder](https://github.com/mhajder))
 
Would you like to contribute a translation for an additional language?<br> 
Feel free to create a Pull Request against the master branch.

## Issues
Have you found an issue in this software or do you have an question?
[Open an issue in this repo](https://github.com/pe7er/hCaptcha/issues/new)

## Improvements
Would you like to contribute improvements to this code?
Please submit a pull request with the proposed changes against the master branch.

## Changelog

22-Apr-2020 : v1.2.0
<ul>
<li>$ Added French fr-FR language File (@micker)</li>
<li>$ Added Germany de-DE language File (@zero-24)</li>
<li>+ Added PHP 7.0 minimum check (@zero-24)</li>
<li>+ Added privacy message about IP beeing send to hcaptcha.com (@zero-24)</li>
</ul>

21-Apr-2020 : v1.1.0
<ul>
<li>$ Added Dutch nl-NL language File (@pe7er)</li>
<li>$ Added Polish pl-PL language File (@mhajder)</li>
<li>+ Added Theme configuration: Light / Dark</li>
<li>+ Added Size configuration: Normal / Compact</li>
</ul>

20-Apr-2020 : v1.0.0
<ul>
<li>+ Added Update server URL</li>
</ul>

10-Apr-2020 : v1.0.0-RC1
<ul>
<li>$ Added English en-GB language File (@pe7er)</li>
<li>+ Added ACL check to Dashboard + Profiles view</li>
</ul>
