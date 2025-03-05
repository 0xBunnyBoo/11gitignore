node_modules
/out

.env
.env.production
.env.local
.env_main
concatenated-output.ts
embedding-cache.json
packages/plugin-buttplug/intiface-engine

node-compile-cache

.idea
.vscode
.zed
.DS_Store

dist/
# Allow models directory but ignore model files
models/*.gguf
pgLite/

cookies.json

db.sqlite
searches/
tweets/

*.gguf
*.onnx
*.wav
*.mp3

logs/

test-report.json
content_cache/
test_data/
tokencache/
tweetcache/
twitter_cookies.json
timeline_cache.json

*.sqlite

# Character configurations
characters/**/secrets.json
characters/**/*.env
characters/**/*.key
characters/**/private/

packages/core/src/providers/cache
packages/core/src/providers/cache/*
cache/*
packages/plugin-coinbase/src/plugins/transactions.csv

tsup.config.bundled_*.mjs

.turbo
.cursorrules
.pnpm-store
instructions.md
wallet_data.txt

coverage
.eslintcache

agent/content

eliza.manifest
eliza.manifest.sgx
eliza.sig

packages/plugin-nvidia-nim/extra
packages/plugin-nvidia-nim/old_code
packages/plugin-nvidia-nim/docs

# Edriziai specific ignores
characters/edriziai-info/secrets.json

# Bug Hunter logs and checkpoints
scripts/bug_hunt/logs/
scripts/bug_hunt/logs/*.log
scripts/bug_hunt/checkpoints/
scripts/bug_hunt/checkpoints/*.json
scripts/bug_hunt/reports/
scripts/bug_hunt/reports/*.md

lit-config.json

# Configuration to exclude the extra and local_docs directories
extra
**/dist/**

ton_nft_metadata/
ton_nft_metadata/*

ton_nft_images/
ton_nft_images/*
