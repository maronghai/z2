const fs = require('fs')

function zz(file) {
  const txt = fs.readFileSync(file, { encoding: 'utf8' })
  const code = txt.replaceAll(/(?: {3,};.*?)?\r?\n/g, '')
  return code
}

function re(file, flag = 'g') {
  const code = zz(file)
  return new RegExp(code, flag)
}

module.exports = {
  zz,
  re
}
