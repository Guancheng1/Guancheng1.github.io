---
title: "Deepfake Detection"
excerpt: "Fake media poses an ever-increasing threat to society. Deepfake technology represents the state of the art in
generating fake media, such as images and videos. Deepfakes are artificial images, video, and audio which can
be nearly impossible for humans to differentiate from real media. This presents threats to our technological
lifestyles and media-dominated culture through the possibility of malicious intervention and cybersecurity
risks. We propose to detect fake media by creating and maintaining a list of “valid” media. As original works
of media are created and uploaded to a platform (regardless of where), we will also add a hashed copy of
this media to a global list. Obviously, with this approach it is impossible to capture all valid media that
exists or has existed - in this detection method, we restrict our scope to news media such as television news
and online publications, since this is comparatively simple to manage and is an area where fake media is
particularly damaging. Ideally, we will expand the scope of the detection mechanism as the tools we develop
for detection improve. Further development is needed here to turn this into a viable solution for all media,
as simply backing up all media is a brute force solution. Here, news media serves as a motivating example
that is both important and approachable.<br/><img src='/images/deepfake.jpeg'> <br/> <a href=“https://github.com/ahmedh409/deepfake-detection”> [Code Base] </a> <a href=“/files/Deepfake_Summary.pdf”> [Project Overview] </a>"
collection: portfolio
---
Current deepfake detection techniques rely almost exclusively on identifying subtle flaws in fake media,
e.g. a tiny irregularity in the blinking pattern of a face. Detecting these irregularities is done primarily using
machine learning techniques, where private corporations or research institutions construct models with huge
amounts of data. Using pure ML approaches is inadvisable for a few reasons: a) these models are trained on
data which covers attacks discovered before the date of model creation; b) these models need to be recreated
from scratch each time; c) they are generally not openly-available for the public to use due to sunk costs;
d) when new detection models are published, deepfake generation techniques gain a new adversary to train
against, and the task of detecting them gets more difficult. we present our ideas for a detection framework of "perceptographic” hashing Rather than approaching the cat-and-mouse game of training models, finding
new attacks, and training better models, we take the assumption that deepfakes will someday be truly in-
distinguishable from reality and that a different, more fundamental approach is necessary.

An example:
-
Imagine several prominent news publishers (e.g. CNN, New York Times, etc.) decided to work together
to prevent the proliferation of altered versions of their original content. The publishers would maintain a
collective list of media that they have published; each time one of them publishes a new artifact, such as
an article or a video, they will automatically add the hash of the artifact (“perceptographic” hash) to the
global list (blockchain). If a random person on the internet wants to check the validity of a news artifact,
they could do so through some interface (e.g. web extension, website, etc.) by checking if the hash of the
artifact is in the list of accepted hashes.
Furthermore, this process could be automated to give some type of confirmation of validity whenever a
secondary news source references the original and makes use of one of the artifacts, such as by showing a
video originally published by one of the news publishers in the network. For example, if NYT uses a video
originally created by CNN, it could have a “verified” checkmark in the top right corner, or similar, to prove
the validity of the embedded media. If the shared list of hashes is publicly available, then this system has the
added benefit of allowing individuals to verify validity locally, which provides transparency and eliminates
the need for trust in an institution.
