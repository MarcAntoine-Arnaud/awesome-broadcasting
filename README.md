# Awesome Broadcasting
A curated list of amazingly awesome open source resources for broadcasters inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php) and [Awesome SysAdmin](https://github.com/kahun/awesome-sysadmin). Check [Awesome SysAdmin](https://github.com/kahun/awesome-sysadmin) for IT related projects.

* [Awesome Broadcasting](#awesome-broadcasting)
  * [Audio over IP](#audio-over-ip)
  * [Codecs](#codecs)
  * [Companion Screens](#companion-screens)
  * [Connected TVs](#connected-tvs)
  * [Distributed Media Processing](#distributed-media-processing)
  * [DVB & WiFi](#dvb--wifi)
  * [Graphics & Video Playout](#graphics--video-playout)
  * [Hybrid Radio](#hybrid-radio)
  * [Media Players](#media-players)
  * [Metadata](#metadata)
  * [Multimedia content processing](#multimedia-content-processing)
  * [Network & Storage Testing](#network--storage-testing)
  * [Quality Control](#quality-control)
  * [Radio Production](#radio-production)
  * [Software-defined radio](#software-defined-radio)
  * [Subtitling](#subtitling)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Websites](#websites)
* [Contributing](#contributing)

<!-- This page is available on http://ebu.io/opensource -->
## Audio over IP

* [Kamailio](http://www.kamailio.org/) - Open SIP server. Commonly used SIP server for Audio contribution over IP using SIP (EBU ACIP)
* [PJSIP](http://www.pjsip.org/) - Open Source multimedia library implementing SIP, SDP, RTP, STUN, TURN, and ICE. Used in some contribution equipment (dual licensing).
* [OpenOB](https://jamesharrison.github.io/openob/) - Open Outside Broadcast project for radio contribution links and studio-transmitter links based on Opus.

## Codecs

* [Opus](http://www.opus-codec.org) - Opus is a totally open, royalty-free, highly versatile audio codec. 
* [FLAC](https://www.xiph.org/flac/) - FLAC Free Lossless Audio Coding. Used by some broadcaster for audio exchange, storage.
* [Lame](http://lame.sourceforge.net/) - Lame, high quality MPEG Audio Layer III (MP3) encoder. (Warning, MP3 is not royalty free!)
* [TwoLame](http://www.twolame.org/) - TwoLame, MPEG Audio Layer 2 (MP2) encoder.

## Companion Screens

* [dvbcss-synctiming](https://github.com/BBC/dvbcss-synctiming) - dvbcss-synctiming is a system for measuring how accurately a TV or companion are synchronised.
* [pydvbcss](https://github.com/BBC/pydvbcss) - pydvbcss is library implementing the DVB Companion Screens and Streams protocols for accurately synchronising media playback between TVs and companions.

## Connected TVs

* [Cross-Platform Authentication](http://ebu.io/project/cpa) - CPA offers an open standard for associating any media device with an online identity.
* [TAL](http://fmtvp.github.io/) - The TV Application Layer (TAL) is an open source library for building applications for Connected TV devices.

## Distributed Media Processing

* [StormCV](https://github.com/sensorstorm/StormCV) - Apache Storm + OpenCV = large scale distributed image and video analysis.

## DVB & WiFi

* [DTT 2 IP](https://github.com/ebu/dtt2ip) - Broadcast to IP conversion for Wifi indoor coverage.
* [DVB Inspector](http://dvbinspector.com/) - DVB Inspector is an open-source DVB analyzer.
* [DVBlast](http://www.videolan.org/projects/dvblast.html) - DVBlast is a simple and powerful MPEG-2/TS demux and streaming application.
* [Opencaster](http://www.avalpa.com/the-key-values/15-free-software/33-opencaster) - OpenCaster is a free and open source MPEG2 transport stream data generator and packet manipulator.
* [WiFiBroadcast](https://befinitiv.wordpress.com/wifibroadcast-analog-like-transmission-of-live-video-data/) - Analog-like transmission of live video data.

## Graphics & Video Playout

* [Aurena](https://github.com/thaytan/aurena) - Aurena is a network distributed media playback system.
* [CasparCG](http://www.casparcg.com/) - CasparCG is a professional graphics and video play-out software, proven in 24/7 broadcasts since 2006
* [i-Score](http://i-score.org/) - A free and open-source intermedia sequencer

## Hybrid Radio

* [RadioDNS Manager](https://github.com/ebu/radiodns-plugit) - A platform to manage Hybrid Radio static services such as RadioVIS, RadioEPG and Service Following.
* [RadioTag.js](https://github.com/ebu/radiotag.js) - RadioTag client library in javascript.
* [RadioVis Html Player](https://github.com/ebu/radiovis-html5player) - RadioVis Player using WebSocket.

## Media Players

* [Dash.js](https://github.com/ebu/dash.js) - A reference client implementation for the playback of MPEG DASH via Javascript and compliant browsers.
* [Kodi](https://github.com/xbmc/xbmc) - A software media player and entertainment hub for digital media.
* [Peaks.js](http://waveform.prototyping.bbc.co.uk/) - Browser-based audio waveform visualisation.
* [VLC](http://www.vlc.org) - Simple, fast and powerful media player. 
* [GPAC](http://gpac.wp.mines-telecom.fr/home/) - Multimedia player, packager and tools

## Metadata

* [BMXlib](http://sourceforge.net/projects/bmxlib/) - Library and utilities to read and write broadcasting media files. Primarily supports the MXF file format.

## Multimedia content processing

* [AvTranscoder](https://github.com/avTranscoder/avTranscoder) - Based on FFmpeg/LibAV libraries to support various video and audio formats, avTranscoder provides the high level API to re-wrap or transcode media easily. It also provide bindings for any usage in Java or Python.
* [Codem-isoboxer] (https://github.com/madebyhiro/codem-isoboxer) A small browser-based MPEG-4 (ISOBMFF) parser.
* [FFmpeg](http://ffmpeg.org) - A complete, cross-platform solution to record, convert and stream audio and video.
* [FFmbc](https://code.google.com/p/ffmbc/) - FFmpeg customized for broadcast and professional usage.
* [GStreamer](https://gstreamer.freedesktop.org/) - A library for constructing graphs of media-handling components.
* [L-SMASH](https://github.com/l-smash/l-smash/) - A rigidly spec-compliant ISOBMFF library, which has full DASH muxing support.
* [LibAV](https://libav.org/) - Open source audio and video processing tools.
* [Libebur128](http://github.com/jiixyj/libebur128) - A library that implements the EBU R 128 standard for loudness normalisation.
* [Loudness Validator](https://github.com/mikrosimage/loudness_validator) - A set of applications to analyse, visualise and correct the loudness.
* [MP4Box.js](https://github.com/gpac/mp4box.js) - JavaScript library to process MP4 files in the browser (and in NodeJS).
* [Open Broadcast Encoder](https://github.com/ob-encoder) - Broadcast encoder built from Open Source components.
* [Photon](https://github.com/Netflix/photon) - Implementation of the SMPTE Material Exchange Format (MXF) file specification.
* [SoX](http://sox.sourceforge.net/) - The Swiss Army knife of sound processing programs. 
* [TuttleOFX](http://www.tuttleofx.org/) - TuttleOFX is an open source image processing framework based on OpenFX plugin standard.
* [UPipe](https://github.com/cmassiot/upipe/) - Upipe is primarily designed to be the core of a multimedia player, transcoder or streamer.
 
## Network & Storage Testing

* [BBC Media Storage Meter](http://sourceforge.net/projects/msmeter/) - An application for the testing of network attached storage, originally assumed to be used for the streaming of professional media.

## Quality Control

* [MediaConch](https://mediaarea.net/MediaConch/) - Implementation checker, policy checker, & reporter for Matroska, FFV1, & PCM.
* [MediaInfo](https://mediaarea.net/en/MediaInfo) - MediaInfo provides a convenient unified display of the most relevant technical and tag data for video and audio files.
* [QCTools](https://github.com/bavc/qctools) - Quality Control tools for video preservation to analyse digitized video files
* [Sonic Visualiser](http://www.sonicvisualiser.org/) - An application for viewing and analysing the contents of music audio files.

## Radio Production

* [Audacity](http://audacity.sourceforge.net/) - Cross-platform software for recording and editing sounds
* [Airtime](https://www.sourcefabric.org/en/airtime/) - Radio management application for remote broadcast automation (via web-based schedule)

## Software-defined radio

* [CRC mmbTools](http://mmbtools.crc.ca/) - Original Tools for DAB digital radio multiplexing and software defined radio modulation.
* [ODR mmbTools](http://www.opendigitalradio.org) - Fork, continuation of CRC mmbTools. Adding new features for 24/24 365/365 live operation, DAB+, associated data (slideshow, text), distributed infrastructure, SFN.

## Subtitling

* [CCExtractor](http://ccextractor.sourceforge.net/about-ccextractor.html) - A tool that analyzes video files and produces stand-alone subtitle files.
* [GStreamer TTML subtitling package](https://github.com/bbc/gst-ttml-subtitles) - A means for GStreamer pipelines to parse and render  EBU-TT-D (TTML) subtitles. 
* [EBU-TT-D Subtitling within dash.js](https://github.com/ebu/dash.js/tree/ebu-subtitling-dev) - The original fork of dash.js to experiment with XML based subtitles like EBU-TT-D within dash.js. Uses an HTML/CSS overlay. Has since been integrated into [dash.js](https://github.com/ebu/dash.js).
* [EBU-TT-D W3C XML Schema](https://github.com/ebu/ebu-tt-d-xsd/) Informative EBU-TT-D XML Schema to support the implementation of EBU Tech 3380.
* [IRT EBU-TT-D Application Samples](https://github.com/IRT-Open-Source/irt-ebu-tt-d-application-samples) - EBU-TT-D sample files, related PNG images and mp4 videos showing how they should be rendered.
* [Subtitling Conversion Framework (SCF)](https://github.com/Irt-Open-Source/scf) - A set of modules for converting subtitle formats. Main target is the conversion of EBU STL and EBU-TT subtitle files. Alpha release.
* [Timed Text Toolkit (ttt)](https://github.com/skynav/ttt) - A collection of related tools that provide support for or make use of the W3C Timed Text Markup Language (TTML).

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [BBC R&D](http://bbc.co.uk/rd) - BBC Research and Development. Checkout the weekly notes.
* [3D CineCast](http://3dcinecast.blogspot.ch/) - A curation about new media technologies.
* [Canal+](http://canalplus.github.io/) - CANAL+ Open Source Community.

## Websites
*Useful broadcasting related websites.*

* [EBU.io](http://www.ebu.io) - A platform for agile collaboration.

<!-- This page is available on http://ebu.io/opensource -->

# Contributing
Please see [CONTRIBUTING](https://github.com/ebu/awesome-broadcasting/blob/master/CONTRIBUTING.md) for details.
