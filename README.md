| Layer             | Technology                               | Purpose                                                  |
| ----------------- | ---------------------------------------- | -------------------------------------------------------- |
| Backend language  | **Go**                                   | Main application and game logic                          |
| HTTP router       | **Chi**                                  | Lightweight, idiomatic REST routing                      |
| Database          | **PostgreSQL**                           | Users, matches, predictions, leagues, points             |
| Database driver   | **pgx/v5**                               | Fast PostgreSQL access from Go                           |
| SQL layer         | **sqlc**                                 | Generates type-safe Go code from SQL                     |
| Migrations        | **Goose**                                | Database schema migrations                               |
| Cache / jobs      | **Redis**                                | Caching, rate limiting, live updates and background jobs |
| Authentication    | **Secure cookie sessions**               | Login without exposing tokens to browser JavaScript      |
| Live updates      | **Server-Sent Events initially**         | Push match and leaderboard updates to browsers           |
| Frontend          | **React + TypeScript + Vite**            | Game interface                                           |
| UI styling        | **Tailwind CSS**                         | Fast responsive interface development                    |
| Data fetching     | **TanStack Query**                       | API state, caching and automatic refresh                 |
| Forms             | **React Hook Form + Zod**                | Prediction and authentication validation                 |
| Football data     | **API-Football**                         | Fixtures, results, match status and live scores          |
| Local development | **Docker Compose**                       | Go, PostgreSQL, Redis and frontend                       |
| Reverse proxy     | **Caddy**                                | HTTPS, compression and routing                           |
| CI/CD             | **GitHub Actions**                       | Tests, builds and deployment                             |
| Monitoring        | **OpenTelemetry + Prometheus + Grafana** | Metrics and operational visibility                       |
| Logging           | **Go `slog`**                            | Structured JSON logs                                     |
