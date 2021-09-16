# graydavid-style-parent

graydavid-style-parent is a parent pom for all projects in the `io.github.graydavid` groupId that want style rules applied in addition to what's already defined in `graydavid-parent`. (This current project exists in addition to `graydavid-parent`, since this current project uses `graydavid-style` which uses `graydavid-parent` itself. So, the current project allows us to avoid circular dependencies.).

## Adding this project to your build

This project follows [semantic versioning](https://semver.org/). It's currently available via the Maven snapshot repository only as version 0.0.1-SNAPSHOT. The "0.0.1" part is because it's still in development, waiting for feedback or sufficient usage until its first official release. The "SNAPSHOT" part is because no one has requested a stable, non-SNAPSHOT development version. If you need a non-SNAPSHOT development version, feel free to reach out, and I can build this project into the Maven central repository.

##Contributions

Contributions are welcome! See the [graydavid-parent](https://github.com/graydavid/graydavid-parent) project for details.