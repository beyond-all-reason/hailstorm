Build using

```bash
curl -o lib/hailstorm/tachyon/tachyon.proto https://raw.githubusercontent.com/beyond-all-reason/tachyon/master/protos/tachyon.proto
protoc --elixir_out=gen_descriptors=true:. lib/hailstorm/tachyon/tachyon.proto
```

Alternately there is a bash script in `bin/proto_build` to perform the above action.
