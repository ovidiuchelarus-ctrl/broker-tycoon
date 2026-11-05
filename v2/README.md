# Broker Tycoon v2

Play: https://ovidiuchelarus-ctrl.github.io/broker-tycoon/v2/

The original game remains at the repository root. This directory contains the redesigned game and its image assets.

Both editions use the existing Supabase `submit_score` and `get_leaderboard` RPCs and share one leaderboard. V2 retains the existing RPC payload format and version field for compatibility. Bot, debug, sandbox and accelerated runs do not submit scores.

No database migration or changes to the original root game are required.
