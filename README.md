<h1 align="center"> ustvgo_to_m3u_free </h1>

Grabs m3u links (for non-VPN channels) from ustvgo.tv

### Check Out The Original Project And README

https://github.com/benmoose39/ustvgo_to_m3u

### My Recommended Usage

##### To Download The Script:

``` bash
git clone https://github.com/Edwin-Zarco/ustvgo_to_m3u_free.git
```

##### To Run Manually:

```
cd ustvgo_to_m3u_free
chmod +x autorun.sh
./autorun.sh
```

##### To Run Automatically Every 4 Hours:

Run the steps in the second section (To Run Manually) first.

```
crontab -e
```

Add this at the end of the file in a new seperate line.

```
0 */4 * * * /home/(USER)/ustvgo_m3u_free/autorun.sh
```

Save and exit. 

The newly generated m3u file in the ustvgo_to_m3u_free folder is ready to be used, but I recommend testing it out in a media player like MPV or VLC to check if it works properly.

### Connect With The Community

https://discord.gg/dmgYmAEdee

### Support The Original Project

https://www.buymeacoffee.com/benmoose39
