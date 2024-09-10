fabric -h
usage: fabric -h
Usage:
  fabric [OPTIONS]

Application Options:
  -p, --pattern=                    Choose a pattern
  -v, --variable=                   Values for pattern variables, e.g. -v=$name:John -v=$age:30
  -C, --context=                    Choose a context
      --session=                    Choose a session
  -S, --setup                       Run setup
      --setup-skip-update-patterns  Skip update patterns at setup
  -t, --temperature=                Set temperature (default: 0.7)
  -T, --topp=                       Set top P (default: 0.9)
  -s, --stream                      Stream
  -P, --presencepenalty=            Set presence penalty (default: 0.0)
  -F, --frequencypenalty=           Set frequency penalty (default: 0.0)
  -l, --listpatterns                List all patterns
  -L, --listmodels                  List all available models
  -x, --listcontexts                List all contexts
  -X, --listsessions                List all sessions
  -U, --updatepatterns              Update patterns
  -c, --copy                        Copy to clipboard
  -m, --model=                      Choose model
  -o, --output=                     Output to file
  -n, --latest=                     Number of latest patterns to list (default: 0)
  -d, --changeDefaultModel          Change default pattern
  -y, --youtube=                    YouTube video url to grab transcript, comments from it and send to chat
      --transcript                  Grab transcript from YouTube video and send to chat
      --comments                    Grab comments from YouTube video and send to chat
      --dry-run                     Show what would be sent to the model without actually sending it

Help Options:
  -h, --help                        Show this help message
