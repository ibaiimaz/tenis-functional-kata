# Mocha testak

## Instalazioa

Joan jatorrizko direktoriora (`package.json` dagoen tokira) eta exekutatu:

```bash
npm install
```

## Testak exekutatzen

Testak behin exekutatzeko:

```bash
npm test
```

Testak exekutatu eta aldaketa bakoitzaren ondoren automatikoki berriz exekutatzeko:

```bash
npm run tdd
```

Testak kode estaldurarekin exekutatzeko:

```bash
npm run coverage
```

### Zer dakar

* Mocha testak exekutatzeko
* [Sinon JS](http://sinonjs.org/)  stub, spy eta mock-ak behar direnerako
* [Chai](http://chaijs.com/api/bdd) asertzioetarako,
  [`sinon-chai` plugin](https://github.com/domenic/sinon-chai) bidez hedaturik.
  * Defektuz `Expect` estiloa erabiltzen du baina honen ordez `Should` erabil daiteke `test/common.js` fitxategian aldaketa eginez