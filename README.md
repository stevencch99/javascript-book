# ALPHACamp JavaScript Book

Website is generated by <https://jekyllrb.com/>

## Development

    bundle install
    jekyll server

## Deployment

    ssh deploy@<server-ip>
    cd javascript-book
    git pull
    JEKYLL_ENV=production bundle exec jekyll build