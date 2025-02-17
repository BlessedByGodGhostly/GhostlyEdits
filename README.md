P = hookfunction(wait, function(seconds)
    -- Definindo o tempo de espera em um valor extremamente baixo
    local minWait = 0.0000000000000001  -- Ajustado para um valor ainda mais baixo
    return P(minWait)  -- Chama recursivamente a função com um valor mais rápido
end)
