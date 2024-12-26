# My Top 10 Self-Hosted apps

Once you have a server running 24/7 in your life, you'll quickly start wondering if there is more you can do with it. Replace video streaming services, or Google Drive, or host your own Home Automation system. Here's a list of some of my favorite self-hosted app picks.

The [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) list details [Free](https://en.wikipedia.org/wiki/Free_software) Software network services and web applications which can be hosted locally. There is also a [Non-Free](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/non-free.md) page.

<p align="center">
<iframe src="https://player.fireside.fm/v2/dUlrHQih+KXqyZUPK?theme=dark" width="740" height="200" frameborder="0" scrolling="no"></iframe>
</p>

My YouTube channel - [KTZ Systems](https://www.youtube.com/@ktzsystems) - is still in its early days but I'm building a playlist of [self-hosted app spotlights](https://www.youtube.com/playlist?list=PLmaj94hXs3GG9yIc4nB5CdIBQ9nAays0I) you might enjoy.


## 1. Jellyfin

[Jellyfin](https://jellyfin.org/) is the media solution that puts you in control of your media. Stream to any device from your own server, with no strings attached. Your media, your server, your way.

<p align="center">
<img alt="jellyfin-banner" src="../../images/top10/jellyfin.png">
</p>

Jellyfin serves no business model, and is not subject to the gradual enshitification that we've seen with Plex over the years. With no cloud connectivity required for authentication, no random streaming services and snappy performance - a fully featured, local first media server experience awaits. Did I mention that it's completely open source too?

It really is worth a look if you haven't tried it in a while. Client updates are coming thick and fast and the server side of things has improved hugely as well. Jellyfin is the future of media servers, no doubt. Check out episode 87 of the Self-Hosted podcast where we discuss our Jellyfin January challenge and invite the audience to take the challenge with us!

<p align="center">
<iframe src="https://player.fireside.fm/v2/dUlrHQih+B62wpyjN?theme=dark" width="740" height="200" frameborder="0" scrolling="no"></iframe>
</p>

[Plex](https://plex.tv) is the reason you're even reading this page. It's what got me interested in Linux in the first place and is somewhat of a gateway drug for self-hosting and can be run as a [container](https://hub.docker.com/r/plexinc/pms-docker/). However, it is not open source and the general posture of Plex as a company gives me pause. They continue to add features and streaming services that [no-one asked for](https://www.reddit.com/r/PleX/comments/e62nbt/how_do_you_disable_the_new_plex_movies_feature/) - [or wants](https://old.reddit.com/r/selfhosted/comments/zw4k2h/what_has_plex_done_lately_that_you_didnt_like/).

**Similar or related projects:**

* [Plex](https://plex.tv)
* [Emby](https://emby.media/)
* [Kodi](https://kodi.tv/)


## 2. Home Assistant

![home-assistant-logo](../images/top10/ha-logo.png){: align=right width=200 }

Open source home automation that puts local control and privacy first. [Home Assistant](https://www.home-assistant.io/) is a truly remarkable project. At the time of writing it has over 3000 [integrations](https://www.home-assistant.io/integrations/) with all manner of devices, services and hardware supported. This is the true magic of Home Assistant.

A [demo](https://demo.home-assistant.io/#/lovelace/0) is available if you're curious to see it in action. But the real magic comes when you start automating your life to a point where when Home Assistant isn't there, you miss it. Automate the lights, climate control and yes, even your dog (via a bedtime routine) with Home Assistant!

A fantastic resource to learn more about the project is YouTube. [Everything Smart Home](https://www.youtube.com/@EverythingSmartHome), [The Hook Up](https://www.youtube.com/c/TheHookUp), [Intermit.tech](https://www.youtube.com/c/IntermitTech), [Smart Home Solver](https://www.youtube.com/@SmartHomeSolver) and [DigiblurDIY](https://www.youtube.com/c/digiblurDIY) are some of the most well-known channels. This isn’t an exhaustive list but should give you plenty of material to work with if you’re in need of inspiration or buying advice.

Home Assistant can be run as a standalone container, on a Raspberry Pi, as a VM and countless [other ways](https://www.home-assistant.io/getting-started/). The learning curve is real but this project really is worth your time to investigate.

## 3. Immich

![immich-logo](../images/logos/immich-logo-stacked-dark.svg){: align=right width=200 }

[Immich](https://immich.app/) is a self-hosted photo management and backup solution that is better at what it does than any of the major proprietary tech company owned solutions Whilst most people are OK with sending their photos off to the cloud for big-tech to process them, monetize them via AI and what have you, some of us aren't.

Immich does local machine learning on your images to do things like face detection, object search and more. I even [made a video](https://youtu.be/QHWNu_in0Zc?si=XHcfw8xnXwbFBM2B) about it for $dayjob showcasing remote machine learning with remote GPUs as well. The Self-Hosted podcast covered Immich extensively in [episode 110](https://notes.jupiterbroadcasting.com/self-hosted/2023/episode-110/) if you'd like to learn more. It's a really fantastic project and it's well worth a look.

Immich recently [joined FUTO](https://immich.app/blog/2024/immich-core-team-goes-fulltime/). I hope to see that this gives the project the runway it needs to really become the defacto open-source solution for photo management. I wrote about the options in 2021 for [Ars Technica](https://arstechnica.com/gadgets/2021/06/the-big-alternatives-to-google-photos-showdown/) and since then Immich has come out of nowhere.


## 4. Nextcloud

[Nextcloud](https://nextcloud.com/) - The self-hosted productivity platform that keeps you in control.

Surely this pick needs no introduction. Think of Nextcloud somewhat like your own personal Dropbox replacement. Although, that is doing it a disservice because Nextcloud supports *many* more features than Dropbox. Nextcloud provide a [demo](https://try.nextcloud.com) if you'd like to try before you "buy" (Nextcloud is free).

<p align="center">
<img alt="nextcloud-banner" src="../../images/top10/nextcloud-banner.png">
</p>

It can be a bit unreliable and unwieldy to administer at times - especially around update cycles. But once you get a working configuration it's a really handy tool.

[Nextcloud Hub](https://nextcloud.com/hub) brings together several key areas of functionality:

* [Nextcloud Files](https://nextcloud.com/files) - offers universal file access on desktop, mobile and web. Find files with powerful search, share your thoughts in comments or lock files until you are done with them. 
* [Nextcloud Talk](https://nextcloud.com/talk) - delivers on-premises, private audio/video conferencing and text chat through browser and mobile interfaces with integrated screen sharing and SIP integration.
* [Nextcloud Groupware](https://nextcloud.com/groupware) - integrates Calendar, Contacts, Mail and other productivity features to help teams get their work done faster, easier and on your terms.

**Similar or related projects:**

* [Seafile](https://www.seafile.com/en/home/)
* [Filestash](https://github.com/mickael-kerjean/filestash)

## 5. Traefik

![traefik-logo](../images/top10/traefik-logo.webp){: align=right width=200 }

Yes, I know. A reverse proxy isn't the most terribly exciting inclusion in this list but it is one of the most important. [Traefik](https://traefik.io/traefik/) (pronounced "traffic") is my go-to reverse proxy. It can be configured alongside the containers it is proxying in the same [docker-compose](../02-tech-stack/docker-compose.md) yaml file.

Traefik does what any good reverse proxy should in 2025, it integrates with certbot and Let's Encrypt for automated TLS certificate generation for your service. Setup can be a bit complex at first but there's a complete [Traefik 101 guide](../04-day-two/remote-access/traefik101.md) over in the "remote access" section.

The elegance of configuring the ingress rules for a service in the same place as you define the configuration for the service itself makes up for any of the shortcomings due to initial setup complexity in my opinion.

**Similar or related projects:**

* [caddy](https://caddyserver.com/docs/quick-starts/reverse-proxy)
* [nginx](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)
* [PMS reverse proxy comparison](../04-day-two/remote-access/index.md)

## 6. Gitea

![gitea-logo](../images/top10/gitea-logo.png){: align=left width=240 }

A self-hosted, lightweight, yet highly feature rich git server, [Gitea](https://gitea.io) is much more powerful than it might seem at first. Sure, it has all the obivous trappings you'd expect from a code hosting solution such as multi-user support, organisations and a similar merge/fork model to a certain well-known online hub for Git activity.

As of [v1.19](https://blog.gitea.com/release-of-1.19.0/#-gitea-actions-21937) in March 2023 Gitea added Actions, a built-in CI system like GitHub Actions. With Gitea Actions, you can reuse your familiar workflows and Github Actions in your self-hosted Gitea instance.

![gitea](../images/top10/gitea-ui.png)

One of my favourite features of Gitea is that it will automatically mirror remote git repositories locally when a commit is pushed. This makes it really easy to back up your code, and other people's code to your server - just in case. Because it's git the entire repo history is maintained and if for some reason a popular project became the target of a BS [DMCA claim](https://github.blog/2020-11-16-standing-up-for-developers-youtube-dl-is-back/), you're not up the creek without a paddle - so to speak.

Gitea doesn't have the kind of built-in CI features like the largest self-hosted and open source player in this space, Gitlab. But what it lacks in features it makes up for in small footprint and simplicity. These can instead be handled by external applications such as [drone](https://www.drone.io/). I wrote about deploying a site based on mkdocs (like this one) with drone CI [on my blog](https://blog.ktz.me/deploying-mkdocs-using-droneci/).

**Similar or related projects:**

* [Forgejo](https://forgejo.org/faq/) - a recent fork of Gitea
* [Gitlab](https://about.gitlab.com/)
* [Gogs](https://gogs.io/)

## 7. Smokeping

[Smokeping](https://oss.oetiker.ch/smokeping/) keeps track of your network latency. It pings things - both remote and local - and records how much latency there is between you and the target.

It isn't a terribly glamourous application to look at, but it enables you to see historical trends of network performance at a glance extremely easily for up to a year at a time.

<p align="center">
<figure markdown>
<iframe width="740" height="415" src="https://www.youtube.com/embed/IDl_oVe_WwU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<figcaption>In this self-hosted app spotlight we look at SmokePing, a network latency monitoring tool.</figcaption>
</figure>
</p>

## 8. Librespeed

A speed test tool that can be run on your LAN or hosted in the cloud. This is available as a Self-Hosted [container](https://hub.docker.com/r/linuxserver/librespeed) as well as at [librespeed.org](https://librespeed.org/).

<p align="center">
<figure markdown>
<iframe width="740" height="415" src="https://www.youtube.com/embed/zyBT_nOnsKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<figcaption>In this self-hosted app spotlight we look at Librespeed, a self-hosted speed test tool.</figcaption>
</figure>
</p>

This is really useful when you want to test the speed between your current system and wherever you are running this container. Want to test the speed between you and your cloud based VPS? Or check that your wifi is performing well?

By running this container on your LAN you're able to remove the internet from the equation and get a better idea about what's going on your LAN.

## 9. Lychee

[Lychee](https://lychee.electerious.com/) proclaims to be "self-hosted photo-management done right". It does certainly do a very good job at presenting images with a clean interface and makes dividing them up into albums relatively straightforward.

![lychee](../images/top10/lychee.png)

I have a demo instance running at [gallery.ktz.cloud](https://gallery.ktz.cloud) if you'd like to take it for a quick test drive yourself. Lychee isn't really a management app, but it's a pretty good all-round option with no frills to share photos with friends and family.

<figure>
    <iframe src="https://player.fireside.fm/v2/dUlrHQih+OssEQUFF?theme=dark" width="740" height="200" frameborder="0" scrolling="no"></iframe>
    <figcaption><i>Lychee discussion begins at 7 minutes</i></figcaption>
</figure>

There are a *lot* of options in this space - just take a look at [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted#photo-and-video-galleries).

**Similar or related projects:**

* [Photoprism](https://github.com/photoprism/photoprism)
* [Librephotos](https://github.com/LibrePhotos/librephotos)
* [Piwigo](http://piwigo.org/)
* [Immich](https://immich.app/)

## 10. Grafana

[Grafana](https://grafana.com/) itself is graphing tool to display data stored elsewhere. It excels at displaying time-series data like the kind gathered by monitoring tools like [Telegraf](https://blog.linuxserver.io/2017/11/25/how-to-monitor-your-server-using-grafana-influxdb-and-telegraf/) and [Prometheus](https://prometheus.io/). It takes a bit of work to get a dashboard configured just the way you like it but is well worth the effort - after all, who doesn't like a pretty graph?

![grafana](../images/top10/grafana.png)

I've written previously about [monitoring your UPS](https://blog.linuxserver.io/2018/11/15/monitoring-a-ups-with-grafana-on-linux/) with Grafana to better keep track of the energy costs of your server setup.

## 11. Surprise me...

`<insert Spinal Tap reference>`

What are your favourites? Let me know [[@ironicbadger](https://techhub.social/@ironicbadger)] on Mastodon.
