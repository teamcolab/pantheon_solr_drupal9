# Search API SOLR for Pantheon on Drupal 9

This project provides a Drupal 9 compatible pairing of modified search_ap_solr
and search_api_pantheon versions.

## Usage

Add  the repo to repositories section of `composer.json`:

```yaml
        {
            "type": "vcs",
            "url": "git@github.com:Taoti/pantheon_solr_drupal9.git"
        },
```

Then run `composer require taoti/pantheon_solr_drupal9:main-dev`

Proceed as usual in building a Pantheon SOLR search.
