# Elineison Inacio

Profissional de segurança eletrônica construindo sistemas Python para operações de monitoramento por vídeo.

Tenho 16 anos de experiência em ambientes reais de segurança: câmeras, DVRs/NVRs, rotinas de controle de acesso, centrais de monitoramento, suporte em campo e fluxos de atendimento a ocorrências. Hoje uso essa vivência para desenvolver sistemas backend e ferramentas de video analytics que sejam práticos para operação, suporte e troubleshooting.

Meu trabalho atual é focado em serviços Python/FastAPI para análise de permanência em elevadores, monitoramento de acesso carona, monitoramento de calçadas, operações VMS, fluxos de alerta e health checks. Nos projetos públicos, trato Dahua/Intelbras como uma única família operacional, refletindo a forma como esse ecossistema é trabalhado na prática.

Os repositórios abaixo são estudos de caso sanitizados, não cópias de produção. Eles mostram arquitetura, APIs e raciocínio operacional sem expor clientes, credenciais, endpoints privados de câmeras, gravações, SDKs proprietários, URLs de alerta ou histórico de incidentes.

## Portfólio em Destaque

- [Site do Portfólio](https://elineison.github.io/)
- [Análise de Permanência em Elevadores](https://github.com/Elineison/elevator-dwell-analytics)
- [Monitoramento de Acesso Carona](https://github.com/Elineison/carona-access-monitoring)
- [Monitoramento de Calçadas](https://github.com/Elineison/sidewalk-safety-monitoring)
- [Painel de Saúde Operacional VMS](https://github.com/Elineison/vms-ops-health-dashboard)

## Estudos de Caso

### Análise de Permanência em Elevadores

Serviço FastAPI para análise de câmeras de elevador: configuração de ROI, duração de track de pessoa, limite de permanência, cooldown, payload de evento e health checks.

### Monitoramento de Acesso Carona

Estudo de caso para eventos de acesso carona/tailgating: sessões curtas, contagem de objetos, zonas de detecção, zonas proibidas e modelagem de eventos para operação.

### Monitoramento de Calçadas

Módulo de monitoramento de calçadas com ROI, runtime de track de pessoa, regras de permanência, saúde de câmera e evidência sintética para demonstrações públicas.

### Painel de Saúde Operacional VMS

Camada de monitoramento operacional para módulos de video analytics, incluindo checagens de silêncio de alerta quando nenhum evento chega por vários dias.

## Principais Competências

Python, FastAPI, arquitetura orientada a OpenCV, fluxos de analytics orientados a YOLO, REST APIs, conceitos de WebSocket, SQLite, Linux, systemd, operação Dahua/Intelbras, suporte VMS, observabilidade, Git e troubleshooting com visão de campo.

## Ética

Meus repositórios públicos usam dados sintéticos e implementações demonstrativas. Eles não expõem informações de clientes, credenciais de produção, endpoints privados de câmeras, gravações, SDKs proprietários, URLs de alerta ou histórico de incidentes.
