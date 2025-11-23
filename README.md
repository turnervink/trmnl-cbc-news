# CBC News for TRMNL

See the latest CBC / Radio-Canada headlines on your [TRMNL](https://usetrmnl.com).

- Supports selecting CBC or Radio-Canada as the source, as well as a variety of feed options from each
- Show or hide story summaries
- View QR codes to open articles on the full view

## Running

Create `.trmnlp.yml` in the root of the project and add the `custom_fields` values as specified in `src/settings.yml`


Start the server:
```sh
trmnlp serve
```

Then visit http://127.0.0.1:4567/
