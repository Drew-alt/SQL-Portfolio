# QUERY showing top 10 best selling games from 1 table 

select *
from public.game_sales
ORDER BY public.game_sales.games_sold DESC
LIMIT 10
