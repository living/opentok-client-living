# opentok-client-living

This is a copy of the opentok client repository with necessary adaptations for our client.

All rights are owned by opentok (vonage), where we acquired the license to use api video.

The change made was in the cycleVideo method.
It is now possible to pass the deviceId as a parameter.

The change made was necessary because in the new devices the exchange of the camera was lost with multiple cameras.
