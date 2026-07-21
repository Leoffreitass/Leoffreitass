Pesquisador quantitativo independente, focado no mercado brasileiro: estratégias sistemáticas long-only sobre o IBOVESPA, do dado bruto ao backtest. Aberto a oportunidades em pesquisa quantitativa e gestão de risco.

## Projetos

### 🌊 [Serenus](https://github.com/Leoffreitass/serenus)

**Low-vol → HRP → volatility targeting com GARCH(1,1) no universo do IBOVESPA.** Sete experimentos documentados até a estratégia final: o momentum clássico e seus crashes, HRP, GARCH como previsor, momentum residual e a combinação de sinais que *não* funcionou — antes do vencedor: comprar os 15 papéis menos voláteis do índice, alocar por Hierarchical Risk Parity e escalar a exposição pela vol prevista. No backtest (2018–2026, líquido de custos): supera o IBOVESPA em retorno com metade da volatilidade e um terço do drawdown máximo.

### 🌫️ [Neblina](https://github.com/Leoffreitass/neblina)

**Trend following com lógica fuzzy no IBOV.** A tendência tratada como questão de grau, não de interruptor: um sistema de inferência Sugeno converte tendência e volatilidade em exposição contínua (0–100%), com fatores macro (dólar e juros) descontando risco gradualmente e caixa a CDI. A ablação contra a regra dura de MM200 isola o efeito: a graduação fuzzy corta o custo do whipsaw — metade do drawdown com retorno maior. Construído em 3 ciclos de pesquisa com **8 hipóteses pré-registradas em commit** antes de cada backtest (3 aceitas, 5 rejeitadas e documentadas).

**Stack:** Python — pandas, NumPy, SciPy, `arch` (GARCH), scikit-fuzzy, matplotlib.

📫 leonardodelfreitass@gmail.com

---

*Projetos de pesquisa e educação. Nada aqui constitui recomendação de investimento; resultados de backtest não garantem desempenho futuro.*
