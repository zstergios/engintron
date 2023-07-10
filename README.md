![Engintron](https://engintron.com/images/logo/v1.1/engintron_logo_v1.1_900x320_24.png)

_Engintron for cPanel/WHM is the easiest way to integrate Nginx on your cPanel/WHM server. Engintron will improve the performance & web serving capacity of your server, while reducing CPU/RAM load at the same time. It does that by installing & configuring the popular Nginx webserver to act as a reverse caching proxy for static files (like CSS, JS, images etc.) with an additional micro-cache layer to significantly improve performance of dynamic content generated by CMSs like WordPress, Joomla or Drupal as well as forum software like vBulletin, phpBB, SMF or e-commerce solutions like WooCommerce, Magento, OpenCart, PrestaShop and others._

---

### FORKED Engintron v2.1 (Build 20220916) / Updated on September 16th, 2022

[ORGINAL REPO](https://github.com/engintron/engintron)

You'll need root SSH access to your cPanel server. Also check the current requirements (listed lower).

If everything is ok, log in as root and type the following command to INSTALL FORK VERSION (WEBSOCKETS SUPPORT):

```
curl -sSL https://github.com/zstergios/engintron/raw/master/engintron_fork.sh | bash -s -- install
```

If cURL is not available on your system, you can use wget like so:

```
wget --no-check-certificate -O - https://github.com/zstergios/engintron/raw/master/engintron_fork.sh | bash -s -- install
```
