```shell
cd lobe-chat
pnpm install
pnpm run dev

mkdir lobe-chat-db && cd lobe-chat-db
bash <(curl -fsSL https://lobe.li/setup.sh) -l zh_CN
docker compose up -d
```