# Remote Interfaces

## Using the Design UI from another computer or tablet
The design interface can be used from any device on your local network or on the internet. For local network usage, you must obtain your IP address so that you can point the browser on your other computer or tablet to the right place. To find your IP address (on the computer that is running the ABR Engine):

- Windows: Open a command prompt and type `ipconfig`
- MacOS/Linux: Open a command prompt and type `ifconfig` or `ip address`

In these tools, look for the line containing 'IPv4' - this is your local network IP address. Enter this address plus `:8000` at the end in the browser window that you want to do your design work in (for example, `192.168.0.104:8000`). If the ABR engine is running on that computer, the interface should connect. If it does not, check your router and firewall settings.

To connect to the design client from a location outside your local network, you'll need to set up port forwarding on your router.

## Using the remote ABRPlayer
We also provide a remote viewer for ABR (see the ABRPlayer programs). To use these programs, follow steps similar to above except enter the IP address in the ABRPlayer instead of in your browser.