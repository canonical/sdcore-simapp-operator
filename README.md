<div align="center">
  <img src="./icon.svg" alt="ONF Icon" width="200" height="200">
</div>
<br/>
<div align="center">
  <a href="https://charmhub.io/sdcore-simapp"><img src="https://charmhub.io/sdcore-simapp/badge.svg" alt="CharmHub Badge"></a>
  <a href="https://github.com/canonical/sdcore-simapp-operator/actions/workflows/publish-charm.yaml">
    <img src="https://github.com/canonical/sdcore-simapp-operator/actions/workflows/publish-charm.yaml/badge.svg?branch=main" alt=".github/workflows/publish-charm.yaml">
  </a>
  <br/>
  <br/>
  <h1>SD-Core AUSF Operator</h1>
</div>

A Charmed Operator for SD-Core's SIM subscription app (SIMAPP) component. 

## Usage

```bash
juju deploy sdcore-simapp --trust --channel=edge
```

## Image

- **simapp**: `omecproject/simapp:main-a4f741a`
