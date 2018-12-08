# Media-Library-management-tools
Docker Compose file for the most known media management toold




* [Sonarr](https://sonarr.tv/)
   * TV PVR (personal video recorder): Automatically downloads my requested shows within the quality range that I want. Ties in to torrent trackers/usenet indexers for search, and torrent downloaders/usenet downloaders for content retrieval. I personally use torrents with private trackers, so the rest of my setup caters to torrents.
* [Radarr](https://radarr.video/)
   * Movies PVR: Automatically downloads my requested movies within the quality range that I want - very similar setup to Sonarr (Sonarr is the original PVR in this style, several other things based on it)
* [Lidarr](https://lidarr.audio)
   * Music: Automatically downloads my requested music within the quality range that I want. It's in beta, but it works well enough and is always getting better.
* [Jackett](https://github.com/Jackett/Jackett)
   * Tracker aggregator/translator: Not all of my trackers are natively compatible with Sonarr/Radarr/Lidarr, so I have Jackett as a man-in-the-middle processor to provide a background API interface for content searches.
* [Ombi](https://ombi.io/)
   * Search/request portal: A clean, easy to use web portal for Movie/TV/Music requests. I have mine externally-facing so I can access it across the internet. I search for the item I want, hit request, and not to long afterward I'll get a notification that the requested item has been downloaded and added to my server.
* [Plex](https://plex.tv)
   * Media server: There are other options out there, but I like Plex the best. Handles most of the metadata and library management for Movies, TV, and Music
* [Transmission](https://transmissionbt.com/)
   * Torrent downloader: Again, many other options, but I've been using Transmission for a really long time and they have always been a good option for me. Runs well in Docker.
* [LazyLibrarian](https://github.com/DobyTang/LazyLibrarian)
   * eBooks/AudioBooks: Automatically downloads my requested eBooks/AudioBooks. Still working on getting it set up completely, but it's got a solid following.
* [Mylar](https://github.com/evilhero/mylar)
   * Comics: Automatically downloads my requested comics. Still working on getting it set up completely, but it's got a solid following.
* [Ubooquity](https://vaemendis.net/ubooquity/)
   * eBook/AudioBook/Comic server: Web portal to manage my downloaded eBook/AudioBook/Comic content. 

Thanks to [u/creedofman](https://www.reddit.com/user/creedofman) for his amazing work.
