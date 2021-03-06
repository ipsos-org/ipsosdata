An event is a simple JSON object (or python dict) with the following structure:
```
{
    'run': int,
    'event': int,
    'lumi': int,
    'event_type': string,
    'data_time': string,
    'dataset': string,
    'vertex': {'position': [float, float, float]},
    'electrons': [
            {'pt' float, 'eta': float, 'phi': float, 'charge': int},
        ],
    'muons': [
            {'pt': float, 'eta': float, 'phi': float', 'charge': int},
        ],
    'photons': [
            {'energy': float, 'eta': float, 'phi': float},
        ],
    'jets': [
            {'energy': float, 'eta': float, 'phi': float}
        ],
    'MET': {'et': float, 'phi': float}
}
```
