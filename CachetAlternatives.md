# 1. PHP Server Monitor

![servers_overview](https://user-images.githubusercontent.com/105150898/191945426-b64cafa4-3a80-4bc1-a017-33c3b6f5e067.png)


https://github.com/phpservermon

PHP Server Monitor is a script that checks whether your websites and servers are up and running. It comes with a web based user interface where you can manage your services and websites, and you can manage users for each server with a mobile number and email address.

Features:
- Monitor services and websites 
- Email, SMS, Discord, Pushover, Telegram and Jabber notifications.
- View history graphs of uptime and latency.
- User authentication with 2 levels (administrator and regular user).
- Logs of connection errors, outgoing emails and text messages.
- Easy cronjob implementation to automatically check your servers.

## Documentation 
http://docs.phpservermonitor.org/en/latest/

### Advantages and disadvantages
+ installation via docker-compose or varantfile
+ latest release 2020 year(pull request 2022 years)
+ possibility of monitoring many pages at once(perhaps???)
+ The data is needed for monitoring (I didn’t find it, you probably need to install it to understand)



# 2. Statping-ng - Status Page & Monitoring Server

<img width="871" alt="68747470733a2f2f696d672e636a782e696f2f7374617475702d68747470736572766963652e706e67" src="https://user-images.githubusercontent.com/105150898/191952013-8d401eae-2302-49c1-8d61-5967cadf872f.png">

Page for monitoring your websites and applications with beautiful graphs, analytics, and plugins. Run on any type of environment.

https://github.com/statping-ng/statping-ng

## Documentation 
https://github.com/statping-ng/statping-ng/wiki

### Advantages and disadvantages
- installation on a separate server than your site or application
- installation on Docker Compose with Automatic SSL or 
- latest release 2022 year
- possibility of monitoring many pages at once(I don't have an answer, maybe there? https://github.com/statping-ng/statping-ng/wiki/Bulk-Import-Services)
- The data is needed for monitoring (I didn’t find it, you probably need to install it to understand)

# 3. Uptime Kuma
( This words " Uptime Kuma" does not mean  Час роботи Кума :)) . Kuma (クマ/熊) means bear bear in Japanese.

A fancy self-hosted monitoring tool
https://github.com/louislam/uptime-kuma

![68747470733a2f2f757074696d652e6b756d612e7065742f696d672f6461726b2e6a7067](https://user-images.githubusercontent.com/105150898/191954584-fcce5cfb-415a-4ac4-9759-364bb78059bc.jpeg)

It is a self-hosted monitoring tool like "Uptime Robot".

## Documentation 
https://github.com/louislam/uptime-kuma/wiki

Live demo https://demo.uptime.kuma.pet

Features:
- Monitoring uptime for HTTP(s) / TCP / HTTP(s) Keyword / Ping / DNS Record / Push / Steam Game Server / Docker Containers.
- Fancy, Reactive, Fast UI/UX.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP), and 90+ notification services, click here for the full list.
- 20 second intervals.
- Multi Languages
- Multiple Status Pages
- Map Status Page to Domain
- Ping Chart
- Certificate Info
- Proxy Support
- 2FA available

### Advantages and disadvantages
- installation on Docker or other
- latest release 2022 year
- possibility of monitoring many pages at once(may be)
- Adding new variables is recommended only through the web interface (which is probably not good)

# 4. Upptime

![Знімок екрана з 2022-09-23 16-02-00](https://user-images.githubusercontent.com/105150898/191966177-e01a80d3-98b0-46e8-b857-85a0e5234c7f.png)

Upptime (https://upptime.js.org) is the open-source uptime monitor and status page, powered entirely by GitHub Actions, Issues, and Pages

## Documentation 
https://upptime.js.org/docs/

# How it works
- GitHub Actions is used as an uptime monitor
- Every 5 minutes, a workflow visits your website to make sure it's up
- Response time is recorded every 6 hours and committed to git
- Graphs of response time are generated every day
- GitHub Issues is used for incident reports
- An issue is opened if an endpoint is down
- People from your team are assigned to the issue
- Incidents reports are posted as issue comments
- Issues are locked so non-members cannot comment on them
- Issues are closed automatically when your site comes back up
- Slack notifications are sent on updates
- GitHub Pages is used for the status website
- A simple, beautiful, and accessible PWA is generated
- Built with Svelte and Sapper
- Fetches data from this repository using the GitHub API

### Advantages and disadvantages
- It is possible to add many urls
- latest release 2020 year(pull request 2021 year)

# 5.Monika
https://github.com/hyperjumptech/monika

Monika is a command line application to monitor every part of your web app using a simple YAML configuration file. Get alert not only when your site is down but also when it's slow.

### Advantages and disadvantage
- Available as a docker image.
- Monika uses a YAML file to define all the settings and configurations. You can find a sample configuration file in the repository called monika.example.yml.
- possibility of monitoring many pages at once (may be here https://monika.hyperjump.tech/guides/examples#multiple-request)
- latest release yesterday









