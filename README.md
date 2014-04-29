IB Controller provides hands-free operation of
[Interactive Brokers](https://www.interactivebrokers.com)
[Trader Workstation](http://www.interactivebrokers.com/en/pagemap/pagemap_APISolutions.php).
It's especially useful for developers of automated trading systems who use
[IB API](http://interactivebrokers.github.io). Features include:

* Automates Trader Workstation (TWS) and IB Gateway (excluding the FIX mode)
* Completes login dialog with credentials from an ``.ini`` file or command line
* Handles dialog boxes which TWS presents during programmatic trading activities
* Offers simple encryption of IB passwords if desired
* Keeps TWS running indefinitely by handling TWS time-based exits
* Allows TWS to be terminated at a specified time on a specified day of the week
* Dismisses various dialog messages (eg version updates, daily tips, IB API
  connections etc)
* Exposes a [telnet](http://en.wikipedia.org/wiki/Telnet) control protocol to
  ``STOP`` the GUI or ``ENABLEAPI`` for IB API client access

We welcome your involvement and contributions! If you like the project, please
click the GitHub "Star" or "[Fork](../../fork)" button. We also invite you to
join the [contributor list](../../graphs/contributors) by submitting
[pull requests](../../pulls). We also thank past contributors to the original
SourceForge project: Richard King, Steven Kearns and Ken Geis.

IB Controller is licensed under the
[GNU General Public License](http://www.gnu.org/licenses/gpl.html) version 3.

Downloads
---------
* **The [latest official release ZIP](https://github.com/ib-controller/ib-controller/releases/latest)
  is recommended for most users**
* [Prior releases](https://github.com/ib-controller/ib-controller/releases) are
  also available
* Arch Linux users can install the
  [ib-controller](https://aur.archlinux.org/packages/ib-controller/) package
  from AUR (includes lots of server-oriented features such as multiple daemons,
  systemd units, headless/virtual framebuffer support etc)
* Developers may wish to embed IB Controller for integration testing convenience
  (eg see projects
  [GoIB](https://github.com/gofinance/ib/testserver) and
  [IB Connect](https://github.com/benalexau/ibconnect/testserver))

User Guide
----------
Please see the [IB Controller User Guide](userguide.md) for installation and
usage instructions.

Support
-------
* **The [TWSAPI Yahoo Group](https://groups.yahoo.com/neo/groups/TWSAPI/info)
  is encouraged for end user usage questions and support**
* Bugs can be reported in the
  [GitHub Issue Tracker](https://groups.yahoo.com/neo/groups/TWSAPI/info)
* Please submit new features, fixes and other contributions as
  [pull requests](../../pulls) to facilitate rapid inclusion in the project