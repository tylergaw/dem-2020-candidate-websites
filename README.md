# 2020 Democratic Presidential Candidate Websites
(NOTE: These are quick stats I ran in Chrome with Lighthouse audits, not gospel)

### Quick tidbits
- None of the sites use a service worker
- Warren and Booker's are the only ones with zero reported color contrast issues
- If I had to vote today 100% based on website design, I'd vote for Gillibrand. I think her site is the best looking and the use of [navigo](https://fonts.adobe.com/fonts/navigo) is excellent. Who would be your pick and why?

### SSL Reports
- **Grade A**: [Harris](https://www.ssllabs.com/ssltest/analyze.html?d=kamalaharris.org)
- TODO Gillibrand
- TODO Booker
- TODO Warren
- TODO Castro
- TODO Klobuchar

### By Total Page Weight (largest to smallest)

| Candidate  | Page Weight |
|------------|-------------|
| Harris     | 6.7 MB      |
| Gillibrand | 4.3 MB      |
| Booker     | 2.6 MB      |
| Klobuchar  | 2.3 MB      |
| Castro     | 745 KB      |
| Warren     | 732 KB      |

### By JavaScript Weight (largest to smallest)

| Candidate  | JS Weight |
|------------|-------------|
| Harris     | 977 KB      |
| Warren     | 340 KB      |
| Booker     | 284 KB      |
| Klobuchar  | 198 KB      |
| Gillibrand | 180 KB      |
| Castro     | 140 KB      |

### CSS Stats
Stats on the primary stylesheet by [cssstats.com](https://cssstats.com)

[**Klobuchar**](https://cssstats.com/stats?link=https%3A%2F%2Famyklobuchar.com%2Fwp-content%2Fthemes%2Fscotchpress%2Fstyle.css)
- 5,858 selectors
- 50 unique colors
- Highest z-index; `99999999999999999999`

### Screenshots of Lighthouse Audits
[](https://kamalaharris.org/)
![Screenshot of kamalaharris.com](https://cl.ly/096e0421f42b/harris.png)

[](https://kirstengillibrand.com/)
![Screenshot of kirstengillibrand.com](https://cl.ly/e84e748dba70/gillibrand.png)

[](https://corybooker.com/)
![Screenshot of coreybooker.com](https://cl.ly/6ef77a97798f/booker.png)

[](https://www.julianforthefuture.com/)
![Screenshot of julianforthefuture.com](https://cl.ly/26c30ca06d34/castro.png)

[](https://elizabethwarren.com/)
![Screenshot of elizabethwarren.com](https://cl.ly/1214cef5beff/warren.png)

[](https://amyklobuchar.com/)
![Screenshot of amyklobuchar.com](https://cl.ly/73ae811450f3/klobuchar.png)
