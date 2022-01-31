# aiohttp_vs_httpx_tester

## Setup
- create python env
  - `python3 -m venv .venv`
  - `source .venv/bin/activate`
- Install python dependencies
  - `pip install -r requirements`
- Install wrk for load testing
  - `brew install wrk`

## Running
  - Start the starlette App
    - `python3 app.py`
  - Load testing using [wrk](https://github.com/wg/wrk)
    - `wrk http://localhost:8000/httpx/single`

## Configuration
  - Point the `HIT_URL` to your domain you want to test on.