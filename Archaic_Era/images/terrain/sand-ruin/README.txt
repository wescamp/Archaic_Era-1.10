# Ruined Sand Castle -  nothing special about the Cyrs,Kyrs terrain.cfg
{DISABLE_BASE_TRANSITIONS  (Cyrs,Kyrs)}
{KEEP_BASE_L               Cyrs                         -2		sand-ruin/dirt}
{KEEP_BASE_L               Kyrs                         -2		sand-ruin/cobbles}
{OVERLAY_PLF             Kyrs           10              -1      rubble	sand-ruin/rocks1}
{OVERLAY_PLF             Kyrs           20              -1      rubble	sand-ruin/rocks2}
{OVERLAY_PLF             Kyrs           30              -1      rubble	sand-ruin/rocks3}
{OVERLAY_PLF             Kyrs           30              -1      rubble	sand-ruin/rocks4}
{OVERLAY_PLF             Kyrs           40              -1      rubble	sand-ruin/rocks5}
{OVERLAY_PLF             Kyrs           40              -1      rubble	sand-ruin/rocks6}
{WALL_TRANSITION      Cyrs                 (!,Cyrs,Kyrs)		sand-ruin/castle}
{WALL_TRANSITION2     Kyrs                 Cyrs             (!,Cyrs,Kyrs)	sand-ruin/keep-castle}
{WALL_TRANSITION      Kyrs                 (!,Kyrs)			sand-ruin/keep}
