**xxedxd**
eddededededed
wsswwswsws
gato malo xd
sywedyede

const generarSlug = (text: string) => {
```
    return text
      .toLowerCase()
      .normalize('NFD')
      .replace(/[\u0300-\u036f]/g, '')
      .replace(/[^a-z0-9]+/g, '-')
      .replace(/^-+|-+$/g, '');
  };
```
~~
PUEDE SER SANTI~~

> ellos no lo saben