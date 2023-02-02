# About

This is a product built by Trip1eLift to practice, proof of concepts, or just for fun.

If you have any suggestions, you can either raise issues or pull requests to any of my projects.

Linkedin: https://www.linkedin.com/in/joseph-chang-856b24176/

## Virtual Avatar

A web-based virtual face renderer inspired by the Metaverse.

There are two ways to use this app: 
1. A Metaverse mirror to see your 3D-rendered face. You can click the setting button on the top left to calibrate or manually tune the position and rotation of your mesh. Click save to save the setting to browser cache storage, so the next time you visit the website, it will be automatically calibrated.
2. Metaverse video chat with your friend. Click the stream button on the top left and either create a room or join a room with a room id. (The stream-matching backend may not always be up and running to support this functionality because the tech stack costs money. If it is down, you can contact me through LinkedIn to deploy the stack.)

Website: https://virtualavatar.trip1elift.com/

Frontend Github: https://github.com/Trip1eLift/virtual-avatar

Backend Github: https://github.com/Trip1eLift/virtual-avatar-stream

The backend architecture is definitely worth a look. It follows best practices. Even better than some enterprises' tech stacks. It's a client-to-client streaming application that's auto-scaling and highly available. All of the resources are protected in VPC private subnets except an ALB that's accepting external traffics.


## Tangle 

A Chinese version of Wordle using Tang Poetry as a word bank.

Github: https://github.com/Trip1eLift/Tangle_wordle4TangPoetry

Website: https://tangle.trip1elift.com/

## License

“Commons Clause” License Condition v1.0

The Software is provided to you by the Licensor under the License, as defined below, subject to the following condition.

Without limiting other conditions in the License, the grant of rights under the License will not include, and the License does not grant to you, the right to Sell the Software.

For purposes of the foregoing, “Sell” means practicing any or all of the rights granted to you under the License to provide to third parties, for a fee or other consideration (including without limitation fees for hosting or consulting/ support services related to the Software), a product or service whose value derives, entirely or substantially, from the functionality of the Software.  Any license notice or attribution required by the License must also include this Commons Cause License Condition notice.

Software: Any software under Trip1eLift
License: Apache 2.0
Licensor: Trip1eLift - Joseph Chang
