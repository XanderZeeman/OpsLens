# OpsLens

**AI-powered log analysis and incident investigation platform.**

OpsLens is a web-based application designed to help developers and system administrators analyze server logs, identify unusual activity, and investigate potential incidents using AI-assisted analysis.

## Core Features

- **Log Processing:** Upload and parse structured and unstructured log files.
- **Log Exploration:** Search, filter, and inspect log events.
- **Analytics:** Visualize system activity, error frequencies, and event trends.
- **Anomaly Detection:** Identify unusual patterns and unexpected changes in log activity.
- **AI Investigation:** Generate evidence-backed incident explanations and troubleshooting recommendations.
- **Incident Reporting:** Generate reports containing relevant findings and log evidence.

## Technology Stack

| Component | Technology |
|---|---|
| Backend | Python, FastAPI |
| Frontend | React, TypeScript |
| Database | PostgreSQL |
| Background Processing | Redis |
| Infrastructure | Docker |
| CI/CD | GitHub Actions |

## Architecture

OpsLens uses a modular backend architecture to separate log ingestion, processing, analysis, and AI-assisted investigation.

See [Architecture Documentation](docs/ARCHITECTURE.md).

## Project Status

Currently in active development.

## License

See the [LICENSE](LICENSE) file.