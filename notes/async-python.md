# Python: async basics

`asyncio.gather` pour l'I/O concurrent. Ne jamais bloquer la boucle avec du CPU-bound:
utiliser `run_in_executor` ou un process pool.
