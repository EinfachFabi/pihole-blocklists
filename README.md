# Pihole-Blocklists
This is a collection of personal block lists for Pi-hole. These lists were created to block specific unwanted domains, advertisements, trackers, or malware that may not be covered by standard lists.

<br></br>

## 📋 Included lists:

Here you will find direct links to the block lists in this repository.

| Name         | List                                                             |
|--------------|------------------------------------------------------------------|
| Master Hosts | https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts |
| Domains      | https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/pro.txt |
| Popup Ads    | https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/popupads.txt |
| Bit List     | https://big.oisd.nl |
| Youtube Ads  | https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/crowed_list.txt |
| Spam         | https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts |
| KAD Hosts    | https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt |
| Tiktok       | https://blocklistproject.github.io/Lists/alt-version/tiktok-nl.txt |
| Porn         | https://blocklistproject.github.io/Lists/alt-version/porn-nl.txt |
| Scam         | https://blocklistproject.github.io/Lists/alt-version/scam-nl.txt |
| Ransomware   | https://blocklistproject.github.io/Lists/alt-version/ransomware-nl.txt |
| Drugs        | https://blocklistproject.github.io/Lists/alt-version/drugs-nl.txt |
| Old Version  | https://blocklistproject.github.io/Lists/alt-version/ads-nl.txt |
| Adaway       | https://adaway.org/hosts.txt |
| Youtube      | https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/youtubelist.txt |
| Mixed        | https://raw.githubusercontent.com/Isaaker/Spotify-AdsList/main/Lists/pi-hole-mixed.txt |

<br></br>

## 🚀 Installation:

To add these lists to your Pi-hole:

1. Open your Pi-hole web interface.

2. Navigate to Adlists (under “Group Management”).

3. Paste the desired URL(s) from the table above into the Address field.

4. (Optional) Add a comment to help you recognize the list later.

5. Click Add.

<br></br>

## ⚠️ Important information & disclaimer

- Use at your own risk: These lists are maintained to the best of our knowledge and belief, but may lead to false positives (incorrectly blocked sites).

- Whitelisting: If a required site no longer works, check the query log and add the corresponding domain to the whitelist.

<br></br>

## 🤝 Contribute

Found a false positive block or have a suggestion for a new domain? Feel free to create an issue in this repository.
