# minigame 2
## Devlog
1) An issue that I had encountered, was a bug I caused by having _timeLeft be subtracted from time, instead of the other way around. This caused the spell hitbox and appearance to occur
infinitely, which was definetly not supposed to happen. Luckily, I was able to do a simple fix by reversing the order and having time be subtracted from _timeLeft properly, and thus having
the around 1 second duration be properly implemented.

2) I believe the period in _spriteRenderer.color, is supposed to call color as a method, function, or object for the class _spriteRenderer to then be instantialized. This is then why the
word 'new' is likely used, as you are creating a new Color set for the _spriteRenderer, using the given values in the paranthesis of (r, 0.2f, 0.2f), which were different from their default
values and thus, 'new'.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
