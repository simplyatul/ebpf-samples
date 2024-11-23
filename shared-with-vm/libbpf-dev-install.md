# Steps to install libbpf-dev

libbpf-dev installed using ```apt``` looks old. So, better to take latest stable version from source directly

```bash
git clone https://github.com/libbpf/libbpf.git
cd libbpf/src
git checkout v1.5.0
sudo make install
```


