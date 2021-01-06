# cpuminerd-docker
## Example

docker run --name cpuminerd --cpuset-cpus="1,3" -d --rm -i cpuminerd:v1.0 ./cpuminer-2.5.1/minerd --url=stratum+tcp://bitcoin.viabtc.com:3333 --userpass=unreal-coin.001:123
