# Bobamaster #

Remember the old days of trying to figure out how to consolidate milktea orders for a team? Are post-it notes for boba runs simply not working? Not to worry, you can have your own Bobamaster to help work out the dirty details for you! Now, you can integrate Bobamaster with slack to make milk tea group orders a delightful, 3 step process:

1) Order boba

2) Get boba

3) Drink boba

Welcome to Bobamaster. Enjoy your stay.

## How do I get set up? ##

First, you will need to get a bot API token from Slack.

Second, rename config-example.coffee to config.coffee and replace the API token inside with your own.

Run `npm install slack-client --save`

Finally, type the following magical words:
 
`coffee bobamaster.boba`

It's that easy!

## Usage ##

Some popular commands include the following:

`@bobamaster new order -teashop [Shop Name]`

This starts a new group order in the channel from the shop name you specified.

`@bobamaster place order -tea [Tea]`

This places an order for milk tea in the currently running order. You can specify sweetness, ice, toppings, and more through their respective flags.

`@bobamaster end order`

This sends the orderer a list of the orders accrued from everyone.

`@bobamaster choose new on call`

This chooses from the members within the channel who will be responsible for milk tea orders for the day.

For the full list of commands, use `@bobamaster help`

## License ##

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
