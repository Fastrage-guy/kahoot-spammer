const KahootSpam = require('kahoot-spam');
const prompt = require('prompt');
let kahoot = KahootSpam;
const colors = require('colors');
function start() {
  console.clear()
  console.log(colors.magenta("Kahoot ") + colors.cyan("spammer ") + colors.green("by ") + colors.red('d') + colors.yellow('u') + colors.green('c') + colors.cyan('k') + colors.magenta('1') + colors.red('3') + colors.yellow('2') + colors.green('9') + colors.cyan('1') + colors.magenta('2'));
  prompt.get(['pin', 'botname', 'botamount'], function (err, result) {
      if (err) { return onErr(err); }
      console.log('success');
      kahoot.spam(result.pin, result.botname, result.botamount)
  });
}
setTimeout(start,2.5);
