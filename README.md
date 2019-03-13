# ObjectPool Sample

This is a basic (and slightly trivial) sample of using the ObjectPool<T> in an ASP.NET Core application.

Here the middleware uses a StringBuilder. As this will be called for every request, pooling and reusing instances is a reasonable idea to avoid allocations per request which will result in extra work for the GC.

BLOG POST COMING SOON!