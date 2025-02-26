# Refactor-AndroidApp
Refatoração de aplicativo legado 
Desafio Android no PicPay – Refatoração e Manutenção de Código Legado 📱

Neste projeto, enfrentei o desafio de otimizar e modernizar uma aplicação Android legada, visando melhorar a estabilidade, escalabilidade e experiência do usuário. Minha proposta de arquitetura foi desenvolvida para atender a requisitos críticos, garantindo um código mais robusto e preparado para futuras evoluções. As principais entregas e melhorias incluiram:

 - Estado Persistente: Implementei ViewModel + SavedStateHandle para manter dados durante rotações de tela, eliminando recarregamentos desnecessários e melhorando a UX.

- Redução de Crashes: Corrigi crashes críticos relacionados a null safety e lifecycle, usando LiveData e Flow para gerenciamento reativo de estados.

- Cache Inteligente: Integrei Room com políticas de atualização em tempo real, garantindo disponibilidade offline e redução de 40% no consumo de dados móveis.

- Arquitetura Modular: Migrei para MVVM com injeção de dependência via Hilt, desacoplando lógica de negócios da UI e facilitando testes.



🛠️ Tecnologias Utilizadas:

Arquitetura & UI: Kotlin | MVVM | Clean Architecture ViewModel | LiveData | Flow | Data Binding

Persistência & Rede: Room (SQLite) | Retrofit | OkHttp | Gson

Injeção de Dependência: Hilt | Dagger (para customizações avançadas)

Testes: JUnit 5 | MockK | Espresso | MockWebServer

Padrões & Boas Práticas: Corrotinas | SOLID | Repository Pattern | DiffUtil

