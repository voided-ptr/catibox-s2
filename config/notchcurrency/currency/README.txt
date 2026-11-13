Custom currency art for Notch Currency
---------------------------------------
Drop your coin texture here as coin.png (a square PNG, 16x16 recommended).
Optional: coin_tails.png for the coin-flip tails side.
The coin's display name is set in the mod's config screen (ModMenu -> Notch Currency -> Currency).

On the next game start, a resource pack called "NotchCurrencyCustom" is generated in the
resourcepacks folder. Enable it once in Options -> Resource Packs and your art shows on
the coin item, the balance HUD, and the coin symbol in chat, everywhere at once.

On a dedicated server, put the same files in the SERVER's config/notchcurrency/currency
folder (and set the name in the server's config file). The skin is pushed to every player
automatically when they join - nothing to distribute.
