Por que a Secret aparece como ***?

Porque o GitHub oculta automaticamente valores de secrets nos logs para proteger dados sensíveis.

O Job 2 consegue ler a BUILD_VERSION do Job 1?

Não. Cada job é isolado. Para compartilhar dados, é preciso usar outputs ou artefatos.

