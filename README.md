# merkle-redeem
Repository containing EnterDAO redeem Merkle distribution data

Important:
- `tokens` represent the amount of ENTR a user must burn to redeem the `eth` amount
- `tokens` do not represent **only** the user's balance at the time of the snapshot (31 Oct). If a user has unclaimed staking, LP, YF rewards, they are added
- `tokens` do not include the 5-15% bonus that some addresses receive due to being Sharded Mind holders
- `eth` and `tokens` do not have direct correlation due to the Sharded Mind holder bonus
