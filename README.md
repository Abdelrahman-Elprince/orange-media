# orange-media

Temporary public bucket for Orange Chinese post media.

Instagram fetches images and video from a public URL with no auth, so files are uploaded here
under content-addressed names, published, and deleted within the hour by `scripts/upload.mjs --cleanup`.
Nothing here is meant to stay: if a file is older than a day it was not cleaned up.
