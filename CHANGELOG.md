# Changelog
All notable changes to this project will be documented in this file.

0.2.21 - 2015-6-21
-------------------
### Added
- Ability to run a remote Docker Compose YAML as a Panamax app (#541)
- Adding imagelayers links to all application and service views (#540)
- Create PMX app from docker-compose.yml upload (#538)

0.2.20 - 2015-6-18
-------------------
### Added
- Contributor code of conduct (#525)
- Ability to view compose representation of a Panamax application (#526, #527, #528, #531)
- Links to imagelayers from search results (#532)

0.2.19 - 2015-5-29
-------------------
### Added
- Set service restart flag to false when dragging into category (#522)
- Play nice with new version of cadvisor (#523)

0.2.18 - 2015-5-6
-------------------
### Added
- Link to ImageLayers image view from image management page (#516)
- CTL Labs about menu (#519)

### Fixed
- Remote Agent token file names getting blanked out (https://github.com/CenturyLinkLabs/panamax-ui/commit/80715bd271d03e5fba7487cfac4667381953b3e8)

0.2.17 - 2015-4-28
-------------------
### Added
- Allow users to download the token for a deployment target (#515)

0.2.16 - 2015-3-31
-------------------
### Updated
- Updated base image

0.2.15 - 2015-3-19
-------------------
### Added
- New Brightbox Logo
- Insecure Registry Messaging (#510)
- Ability to supply absolute Image Paths (#512)

0.2.14 - 2015-2-25
-------------------
### Updated
- Moved to 0.3.0 of panamax-ruby-base (see: https://github.com/CenturyLinkLabs/panamax-ruby-base/commit/08ef298b842f4e48fd254b3c931977ae7f109993)
- Upgraded Rspec (#475)

0.2.13 - 2015-2-17
-------------------
### Changed
- Remove outline from focused links (#9699cb74d52b6b7906d4dbc8ad225f0ab5d92c99)

0.2.12 - 2015-2-10
-------------------
### Added
- Ability to trigger creation of a cluster (#495, #498, #504)
- Ability to view the progress of a job (#499, #500, #500, #503)

0.2.11 - 2014-12-17
-------------------
### Added
- Add capability to display error helper (#468)
- Enable deployment after health check (#469)
- Copy token to clipboard (#474)
- Adding the ability to redeploy a remote deployment (#485)

### Changed
- Update cAdvisor api to 1.2 (#480)

0.2.10 - 2014-12-1
------------------
### Added
- Deployment status (#448)
- Deploy from an application (#452)
- Title text to most pages (#467)

### Changed
- Replace docker index url with docker search url (#458)
- Disable delete button while pending (#459)
 
### Fixed
- Docker run preview of ENV vars (#456)
- Debounce the search input (#463, #437)

0.2.9 - 2014-11-21
------------------
### Added
- Refresh exposed ports if service isn't running on intitial page load (#449)
- Informal time zone format (#450)

### Fixed
- Environment variables without values can now be submitted (#455)

0.2.8 - 2014-11-13
------------------
### Added
- Deployment names (#446)
- Ability to see metadata for a given target (#432)

### Fixed
- CSS issue with Safari 8 browser on service details page and deployment configuration page (#441)
- Click region on the run app button (#442)
- Dialog positioning issue (#447)

0.2.7 - 2014-11-10
------------------
### Added
- Ability to manage deployment targets (#406)
- Ability to deploy a template remotely (#415, #416)
- Ability to view a list of remote deployments (#427, #435)
- Ability to delete a deployment (#433)
- Updated dashboard view (#418)
- tab based service management view (#408)

### Fixed
- Link line wrap issue (#411)
- Service health route for possible dot in name (#405)

### Upgraded
- Rails from 4.1.5 to 4.1.7 (#422)

### Known Issues
- CSS issue with Safari 8 browser on service details page and deployment configuration page

0.2.6 - 2014-10-22
------------------
### Fixed
- Private registry image run (#404)

0.2.5 - 2014-10-20
------------------

### Added
- Updated cAdvisor meter for host and services (#392)
- Private Registries support (#398, #395, #394, #388, #387, #386)
- Additional type icons (#391)

0.2.4 - 2014-10-10
------------------

### Fixed
- Catch malformed, expired or badly scoped Github token (#362, #382, #383)

### Added
- Add capability to update GitHub token (#375)
- Docker Inspect dialog added to service details (#380)


0.2.3 - 2014-10-02
------------------

### Fixed
- Don't show scrollbar on environment variable field (#347)

### Added
- Edit Service Name
- Remove Multiple Images
- Manage Volumes From
- Port management
 - Show ports exposed by the base image in list (#368)
 - Table-based layout for ports information (#369)
 - Show port numbers automatically assigned by Docker (#376)
 - Disable endpoint links when service is not running (#378, #379)


0.2.2 - 2014-09-26
------------------

### Added
- Edit name and value of environment variables (#371)

### Removed
- Removed all contest-related content from application (#370)

### Fixed
- Port mapping bug when host port not specified (#363)


0.2.1 - 2014-09-18
------------------

### Added
- Edit service name (#356)
- New styling for notification links (#357)
- Image management
  - Image size displayed (#358)
  - Batch delete (#360)
- Analytics instrumentation for 'View on Docker Index' link (#361)

### Fixed
- Don't show scrollbar on environment variable field (#347)
- Unintentional service form submission (#348)


0.2.0 - 2014-09-09
------------------

### Added
- Direct links to apps/sources from dashboard (@coen-hyde)
- Support for cAdvisor 0.2.2
- Show 'docker run' string on service details page
- UTC suffix on timestamps

0.1.3 - 2014-09-03
------------------

### Fixed
- Fix icon clipping on template search result display (#343)
- Add a keyword cloud for browsing templates (#340)
- Template details dialog rendering (#333)

0.1.2 - 2014-08-27
------------------

### Added
- Upgraded to Rails 4.1.5
- Text legend for port bindings
- Link target on search results "Learn more" link

### Fixed
- Load remote JavaScript resources via HTTPS (#295)
- Missing validation for exposed ports (#292)
- Firefox issues on Edit Application screen (#307)
- Port binding not showing protocol
- A couple search ui bugs (#335)
- Clicking run template from the modal (#333)


0.1.1 - 2014-08-11
------------------

### Added
- robots.txt
- LICENSE
- Tags loaded for local images as part of search results
- Dashboard for managing apps, local images and template repos
- Template source management
- Checkbox for newsletter subscription when entering GH token
- Link to documentation examples on save template screen
- Custom error pages
- New favicon
- Footer content and links
- Content about template contest

### Deprecated
- Nothing

### Removed
- Boilerplate documentation when saving template

### Fixed
- Formatting on category delete confirmation dialog
- Formatting on documentation dialog
- Nil position bug when moving services between categories

0.1.0 - 2014-08-04
------------------

Initial beta release
