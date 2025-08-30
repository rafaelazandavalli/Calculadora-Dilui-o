valuation_post = valuation_pre + aporte
investidor_pct = (aporte / valuation_post) * 100
novo_percentual_socio = percentual_original * (valuation_pre / valuation_post)
fator_normalizacao = 100 / soma_percentuais_originais
percentual_normalizado = percentual_original * fator_normalizacao
