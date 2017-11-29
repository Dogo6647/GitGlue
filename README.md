# GitHub Pinner
Pin a GitHub profile, a bunch of repositories, or a single repository on your own website with this quick and easy tool.

## Preview
<p align="center"><img src="https://i.imgur.com/iC56hgU.png" width="550px"><br>
  <img src="https://i.imgur.com/IHws5n9.png" width="350px">
<img src="https://i.imgur.com/sAUzE7T.png" width="350px"></p>

## Usage
Simply set the html **data** field with a GitHub profile, repository, or repositories tab url...
```html
<script src="https://s3.amazonaws.com/mackboudreau/GitHubPinner.js"></script>
<div id="github-pinner" data="https://github.com/mackboudreau/CustomSegmentedController"></div>
```

## TODO
* Implement functionality for a "All Repos" element
* Use AWS Cloudfront to serve files to reduce latency on sites
* Add additional option styles for tiles
