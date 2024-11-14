## Welcome to the REVIGET-website Repository

This website is built with [Quarto](https://quarto.org), an open source scientific and technical publishing system.

Note: the `_utils` directory contains helper scripts used when migrating from Wowchemy / Hugo Academic to Quarto.


## Notes to self

### Adding publications
use `just newpub` for creation of new directory and input prompts for new record.

### Adding new people
use `just newperson` for creation of new directory and input prompts for new record.

### Deployment 

- use long-running `updates` branch for deploy previews
- `quarto render` locally and include `_site` in version control
- GitHub action `scp-to-server.yml` deploys to server


### Acknowledgement
We are very grateful to the [Masiello Group Website](https://github.com/MasielloGroup/MasielloGroupWebsite) for providing the quarto source code of their wonderful website, which we used as a foundation for REVIGET website.