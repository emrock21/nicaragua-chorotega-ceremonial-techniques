# Nicaragua Chorotega Ceremonial Pottery Techniques Registry

On-chain registry documenting real, verifiable Chorotega ceramic techniques from Nicaragua.

This contract records:

- Red slip (engobe rojo)
- Negative painting
- Geometric incision
- Zoomorphic modeling
- Spiral motifs
- Bird motifs
- Open-draft kiln firing
- Low-temperature firing
- Other documented Chorotega ceramic practices

Communities include:

- San Juan de Oriente
- Catarina
- Diriomo
- Diria
- San Marcos
- Nandaime

---

## Contract

Deployed on Base:
`0xd0e188bfbf62899d5d263b818a76ced4114b74c8`

🔗 https://basescan.org/address/0xd0e188bfbf62899d5d263b818a76ced4114b74c8#code

---

## Interface

solidity

recordTechnique(
  string region,
  string community,
  string techniqueName,
  string materialType,
  string culturalNote,
  string ritualUse
);

voteTechnique(uint256 id, bool like);

totalTechniques();

---

## Purpose
This registry preserves documented Chorotega ceramic knowledge and ceremonial techniques on-chain.
