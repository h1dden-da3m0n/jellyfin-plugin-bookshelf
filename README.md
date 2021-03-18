<h1 align="center">Jellyfin Bookshelf Plugin</h1>
<h3 align="center">Part of the <a href="https://jellyfin.org/">Jellyfin Project</a></h3>

<p align="center">
<img alt="Plugin Banner" src="https://raw.githubusercontent.com/jellyfin/jellyfin-ux/master/plugins/SVG/jellyfin-plugin-bookshelf.svg?sanitize=true"/>
<br/>
<br/>
<a href="https://github.com/jellyfin/jellyfin-plugin-bookshelf/actions?query=workflow%3A%22Test+Build+Plugin%22">
<img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/jellyfin/jellyfin-plugin-bookshelf/Test%20Build%20Plugin.svg">
</a>
<a href="https://github.com/jellyfin/jellyfin-plugin-bookshelf">
<img alt="MIT License" src="https://img.shields.io/github/license/jellyfin/jellyfin-plugin-bookshelf.svg"/>
</a>
<a href="https://github.com/jellyfin/jellyfin-plugin-bookshelf/releases">
<img alt="Current Release" src="https://img.shields.io/github/release/jellyfin/jellyfin-plugin-bookshelf.svg"/>
</a>
</p>

## About
The Jellyfin Bookshelf plugin enables the collection of eBooks & AudioBooks, with the latter being able to be played through Jellyfin. This plugin uses Google Books as a Metadata provider.

Supported eBook file types:

- epub
- mobi
- pdf
- cbz
- cbr

## Build Process

1. To build and run this plugin you will need [jprm](https://github.com/oddstr13/jellyfin-plugin-repository-manager) as well as [.Net Core 5.x](https://dotnet.microsoft.com/download/dotnet/5.0).

2. Run the build via `jprm`
  ```
  jprm plugin build --output=../artifacts
  ```

3. Place the resulting file in the `plugins` folder of your JF install
