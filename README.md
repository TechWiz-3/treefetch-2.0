## :pray: Ways you can help

**In general:**
* Test treefetch on your system, report any issues, PR any changes you wish to make.
* Take a look at the [utilities](./utils) and help improve them with a PR or suggest something in an issue.

[**`get_desktop`**](./utils/get_desktop)
* Test the utility and help improve it to include more desktop managers and improve it's accuracy
* Work on other methods to get the desktop environment if `XDG_CURRENT_DESKTOP` env variable does not exist

Useful links:
- [neofetch `get_de`](https://github.com/dylanaraps/neofetch/blob/ccd5d9f52609bbdcd5d8fa78c4fdb0f12954125f/neofetch#L1771)
- [desktop related env variables](https://superuser.com/questions/1074068/what-is-the-difference-between-desktop-session-xdg-session-desktop-and-xdg-cur)
- [getting desktop env discussion](https://unix.stackexchange.com/questions/116539/how-to-detect-the-desktop-environment-in-a-bash-script)

[**`get_wm`**](./utils_get_wm)
* Review code and PR any logic issues or any improvements
* Test on your system/s and submit an issue if something is wrong
* Review window managers list for each platform (win, mac, linux)

Useful links:
* [neofetch `get_wm` and `get_wm_theme`](https://github.com/dylanaraps/neofetch/blob/ccd5d9f52609bbdcd5d8fa78c4fdb0f12954125f/neofetch#L1892)

## :face_with_monocle: Origin
This project is a different implementation of another project with similar output, this project is named [tfetch](https://github.com/Endlassy/tfetch). This project is NOT related to the [treefetch](https://github.com/angelofallars/treefetch) project, which is in written in rust and displays physical ascii trees (check it out tho, it's pretty cool).
