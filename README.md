## User Notes for Fedora Kinoite 44

### Documentation
[Fedora Kinoite Documentation](https://docs.fedoraproject.org/en-US/atomic-desktops/)

### Check for Updates
`rpm-ostree upgrade --check`

### Update RPM Packages
`rpm-ostree upgrade`

### Update Flatpaks
`flatpak update`

### Check for a Deployed Update (Pending Update)
`rpm-ostree status`
- if a pending update is staged (pending) it is marked with a small circle coloured in

### Force Update the Deployed (Pending) Update
`sudo rpm-ostree upgrade`
- if it says update was staged reboot to apply it

`sudo systemctl reboot`


### Launch Discover Update App: Alternative way to update System Apps
- Press super key (Windows key)
- A box to type text into appears
- Type Discover
- It should open the discover update app
