# Base SINAPI (formato Excel) — Engenharia Criativa

Hospeda o arquivo **`sinapi.xlsx`** (workbook combinado nacional `SINAPI_Referência` da Caixa,
todas as UFs). Consumido automaticamente pelo app via a variável `SINAPI_STABLE_URL`
(o cron mensal e o botão "Atualizar agora" importam todas as UFs deste arquivo).

**Atualização mensal:** baixe da Caixa o pacote SINAPI no formato Excel, extraia o
`SINAPI_Referência_AAAA_MM.xlsx`, renomeie para `sinapi.xlsx` e substitua aqui (mesmo nome →
o link não muda). A data-base é lida de dentro do arquivo.
