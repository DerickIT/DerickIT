- https://github.com/athul/waka-readme
## Tweaks

There are many flags that you can modify as you see fit.

### Meta Tweaks

| Environment flag | Options (`Default`, `Other`, ...)                                                        | Description                                                                   |
| ---------------- | ---------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| `API_BASE_URL`   | `https://wakatime.com/api`, `https://wakapi.dev/api`, `https://hakatime.mtx-dev.xyz/api` | Use WakaTime compatible services like [Wakapi][wakapi] & [Hakatime][hakatime] |
| `REPOSITORY`     | `<gh_username>/<gh_username>`, `<gh_username>/<repo_name>`                               | Waka-readme stats will appear on the provided repository                      |

### Content Tweaks

| Environment flag    | Options (`Default`, `Other`, ...)                                       | Description                                                                       |
| ------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| `SHOW_TITLE`        | `false`, `true`                                                         | Add title to waka-readme stats blob                                               |
| `SECTION_NAME`      | `waka`, any alphanumeric string                                         | The generator will look for section name to fill up the readme.                   |
| `BLOCKS`            | `░▒▓█`, `⣀⣄⣤⣦⣶⣷⣿`, `-#`, `=>`, you can be creative                      | Ascii art used to build stats graph                                               |
| `CODE_LANG`         | `txt`, `python` `ruby` `json` , you can use other languages also        | Language syntax based highlighted text                                            |
| `TIME_RANGE`        | `last_7_days`, `last_30_days`, `last_6_months`, `last_year`, `all_time` | String representing a dispensation from which stats are aggregated                |
| `LANG_COUNT`        | `5`, any plausible number                                               | Number of languages to be displayed                                               |
| `SHOW_TIME`         | `true`, `false`                                                         | Displays the amount of time spent for each language                               |
| `SHOW_TOTAL`        | `false`, `true`                                                         | Show total coding time                                                            |
| `SHOW_MASKED_TIME`  | `false`, `true`                                                         | Adds total coding time including unclassified languages (overrides: `SHOW_TOTAL`) |
| `STOP_AT_OTHER`     | `false`, `true`                                                         | Stop when language marked as `Other` is retrieved (overrides: `LANG_COUNT`)       |
| `IGNORED_LANGUAGES` | <code> </code>, `Binary YAML JSON TOML`                                 | Hide languages from your stats                                                    |

### Commit Tweaks

| Environment flag  | Options (`Default`, `Other`, ...)                                    |
| ----------------- | -------------------------------------------------------------------- |
| `COMMIT_MESSAGE`  | `Updated waka-readme graph with new metrics`, any reasonable message |
| `TARGET_BRANCH`   | `NOT_SET`, target branch name                                        |
| `TARGET_PATH`     | `NOT_SET`, `/path/to/target/file`                                    |
| `COMMITTER_NAME`  | `NOT_SET`, committer name                                            |
| `COMMITTER_EMAIL` | `NOT_SET`, committer email                                           |
| `AUTHOR_NAME`     | `NOT_SET`, author name                                               |
| `AUTHOR_EMAIL`    | `NOT_SET`, author email                                              |

The first option is the _default_ value of the _flag_, subsequent options are valid values available for the _flag_.
