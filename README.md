# homebrew-tap

Tap de Homebrew de [Nicolás Condeza](https://github.com/NicolasCondezaR).

```bash
brew install NicolasCondezaR/tap/<formula>
```

O en dos pasos, si prefieres añadir el tap una vez:

```bash
brew tap NicolasCondezaR/tap
brew install <formula>
```

## Fórmulas

| Fórmula | Qué es |
|---|---|
| [`sonda`](https://github.com/NicolasCondezaR/sonda) | Proxy depurador de tráfico de desarrollo: HTTP y gRPC, con protobuf decodificado y los trailers preservados |

## Cómo se mantiene esto

Las fórmulas las genera y las escribe [GoReleaser](https://goreleaser.com) cuando
el proyecto de origen publica un tag. **No las edites a mano aquí**: el cambio se
perdería en la siguiente publicación. Lo que hay que corregir vive en el
`.goreleaser.yaml` del proyecto correspondiente.
