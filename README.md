# Trading Strategies — Pine Script

![Pine Script v5](https://img.shields.io/badge/Pine%20Script-v5-blue) ![TradingView](https://img.shields.io/badge/Platform-TradingView-131722) ![License MIT](https://img.shields.io/badge/License-MIT-yellow) ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange)

Repositório de estratégias de trading, indicadores técnicos e scripts Pine Script para uso no TradingView.
Desenvolvido por [ProfIAsorLeo](https://github.com/ProfIAsorLeo) — focado em análise técnica, automação e educação financeira.

---

## Sobre o Projeto

Este repositório reúne estratégias de trading e indicadores técnicos desenvolvidos em **Pine Script v5** para a plataforma **TradingView**. O objetivo é criar ferramentas de análise técnica robustas, bem documentadas e de fácil uso para traders de todos os níveis.

**Principais recursos:**

- Estratégias baseadas em análise técnica clássica e moderna
- - Indicadores personalizados para identificação de tendências e reversões
  - - Scripts de backtest para validação de estratégias
    - - Automação de alertas no TradingView
     
      - ---

      ## Estrutura do Repositório

      ```
      trading-strategies/
      |-- strategies/        # Estrategias completas
      |   |-- trend-following/
      |   |-- mean-reversion/
      |   +-- breakout/
      |-- indicators/        # Indicadores customizados
      |   |-- oscillators/
      |   |-- trend/
      |   +-- volume/
      |-- backtests/         # Resultados de backtests
      |-- docs/              # Documentacao detalhada
      |-- .gitignore
      |-- LICENSE
      +-- README.md
      ```

      ---

      ## Como Usar

      **Pré-requisitos:** Conta no [TradingView](https://www.tradingview.com) (gratuita ou paga) e conhecimento básico de Pine Script.

      1. Acesse o TradingView e abra um gráfico do ativo desejado
      2. 2. Abra o **Pine Script Editor** clicando em Pine Editor na barra inferior
         3. 3. Copie o código do script desejado neste repositório
            4. 4. Cole no editor e clique em **Add to chart**
               5. 5. Configure os parâmetros conforme sua estratégia
                 
                  6. ```pinescript
                     //@version=5
                     indicator("Meu Indicador", overlay=true)
                     plot(close, color=color.blue)
                     ```

                     ---

                     ## Estratégias Disponíveis

                     | Nome | Tipo | Timeframe | Ativo | Status |
                     |------|------|-----------|-------|--------|
                     | EMA Crossover | Trend Following | 1H, 4H | Cripto/Forex | Em breve |
                     | RSI + Bollinger | Mean Reversion | 15M, 1H | Acoes/Cripto | Em breve |
                     | Breakout Range | Breakout | 1D | Futuros | Em breve |

                     ---

                     ## Indicadores Disponíveis

                     | Nome | Categoria | Descrição | Status |
                     |------|-----------|-----------|--------|
                     | Custom RSI | Oscilador | RSI com zonas dinâmicas | Em breve |
                     | Smart EMA | Tendência | EMA adaptativa com alertas | Em breve |
                     | Volume Profile | Volume | Perfil de volume por sessão | Em breve |

                     ---

                     ## Roadmap

                     ✅ Estrutura inicial do repositório
                     ✅ Documentação base (README profissional)
                     ✅ Tópicos e descrição no repositório
                     🔲 Primeira estratégia EMA Crossover
                     🔲 Indicador RSI customizado
                     🔲 Backtest documentado com métricas
                     🔲 Wiki com tutoriais em português
                     🔲 Integração com alertas do TradingView

                     ---

                     ## Contribuindo

                     Contribuições são bem-vindas! Siga os passos abaixo:

                     1. Faça um Fork do projeto
                     2. 2. Crie uma branch: git checkout -b feature/minha-estrategia
                        3. 3. Commit: git commit -m 'feat: adiciona estrategia XYZ'
                           4. 4. Push: git push origin feature/minha-estrategia
                              5. 5. Abra um Pull Request
                                
                                 6. ---
                                
                                 7. ## Licença e Contato
                                
                                 8. Este projeto está sob a licença **MIT**.
                                
                                 9. **Leonardo Cassiano Silva** | [@ProfIAsorLeo](https://github.com/ProfIAsorLeo)
                                
                                 10. [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/leonardo-cassiano-silva-98891936/)
