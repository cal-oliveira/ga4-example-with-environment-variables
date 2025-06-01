# Como implementar Analytics

Como implementar Google Analytics (GA4) em projetos NextJs (possivelemente útil para outros frameworks)

## Tutorial

O arquivo está se encontra em 'src/components/analytics.tsx' e já está pronto, basta apenas copiar e colar, substitua no seu arquivo .env pela sua variavel de ambiente (ID do GA4).
Após isso chame esse componente no seu '\_layout.tsx' dentro do body e antes do children.

## Exemplo

<body>

    <Analytics />
    {children}

</body>
