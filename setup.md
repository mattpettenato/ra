**Tiny Kitchen**
*Functional Requirements:*

 - Place an Order (**POST**) - HP
 - See a list of all orders (**GET**) - K
 - Mark order as Complete (**PATCH**) - K
 - Cancel an Order (DELETE) - Both

*Other Considerations:*

 - Edit a live order (PATCH)
 - Kitchen vs Hungry People (Users)
 - REviews / Comments
 - Menu
 - Kitchen Inventory
 - Error handling (Required)
 - Visual Design

Non-Functional Requirements:
- Low Latency (<= 200ms)
- Available => No Crashes!!! Uptime!!! See something, Anything!!! (Anything but a 404, 500, etc)
- Reliable (eg. persistent) => (POST, GET, PATCH) if i did something, it worked and it persisted
