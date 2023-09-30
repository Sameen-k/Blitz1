## Blitz

During the Blitz, we installed CloudWatch to our EC2 in the public subnet. This allowed us to observe the latency of the application which was originally 40ms. The request to reduce the application's latency can be handled by adding CloudFront (CDN). CloudFront is a service offered by Amazon that can speed up the distribution of the application to users spread across the globe. In simpler terms, it can significantly reduce latency by serving up the web application quicker because of its numerous edge locations.

## System Diagram
![BlitzVPC Diagram-Page-2 drawio (2)](https://github.com/Sameen-k/Blitz1/assets/128739962/5c923967-495a-47a5-8bff-55c33e05815e)

## Resolution

To resolve the latency issue. The CDN CloudFront was incorporated into the overall system design which greatly reduced latency. CloudWatch showed that after CloudFront was added, the latency was reduced to 9.652ms which a huge drop from the previous 40ms.
After this, the web application was loading up faster for users. 

## Purpose
The purpose of this Blitz was to understand how to solve user issues such as latency as well as understand Amazon's tools that can aid in troubleshooting issues.
