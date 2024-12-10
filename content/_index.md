+++
date = '2024-12-05'
+++
# EDLgen # 
<!-- {#main-heading} -->

### Generate EDL files from live triggers over HTTP ###  

EDLgen is a video broadcast, streaming and editing tool for generating EDL (Edit Decision List) files from custom, mappable, "edit events" synced over a live LTC/SMPTE timecode feed. EDLgen listens for incoming events over a network using a simple HTTP REST API. When an event request is received, it will log the event metadata (such as AV channels, edit type, tape number, etc.) into an EDL file with the corresponding timecode for the edit. This allows users to use arbitrary switching software or hardware, so long as it's capable of sending HTTP requests to log their live camera switches and automatically import them as edits into their editing software of choice.

