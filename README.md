# Example Call
This repository contains an an example 0x call requiring a high gas limit for `eth_all` requests, and leverages a state-override parameter. It doesn't seem necessary to go through the trouble of decoding the results, as it's clear that the failed request returns a significanly small set of data than a successful request.

Note: Due to the nature of the requests, it's expected that the overall returned data will vary slightly block-to-block. It's possible to make the request against a specific block number to get a more reproducible test case.
