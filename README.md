Messing around with (aleph)[https://github.com/ztellman/aleph], an async http server based around channels.

For some reason all the futures creatd by my requests are ending up being handled by the same thread, so there's no benefit to the async nature of the thing.  I need to look into that, and/or try using threads directly instead of through futures.
