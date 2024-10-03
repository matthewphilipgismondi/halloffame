Maybe there really is a bashbug command that does what this says, but reading through the code made me laugh a little bit because of how helpful and innocent it sounds. And it has an email address that reminds me of someone I met that was just one more example of being cut off from someone as soon as I showed any sign of interest. Because... well, whatever. It also says DEFEDITOR which is what I feel like I am right now, but I don't edit things people say when I pass them on unless I say what I changed. Apparently I was mistaken for someone who must be notorious for that. And for someone who... [insert every possible thing].

"Bitter, party of one? Your table is ready!" as Travis Hibbs would say. Bless his heart.

I just looked it up, and there apparently is a bashbug command. So maybe this is nothing but the inspiration for the name of the bug. Here is the man page:

bashbug(1) - Linux man page
Name
bashbug - report a bug in bash
Synopsis
bashbug [--version] [--help] [email-address]
Description
bashbug is a shell script to help the user compose and mail bug reports concerning bash in a standard format. bashbug invokes the editor specified by the environment variable EDITOR on a temporary copy of the bug report format outline. The user must fill in the appropriate fields and exit the editor. bashbug then mails the completed report to bug-bash@gnu.org, or email-address. If the report cannot be mailed, it is saved in the file dead.bashbug in the invoking user's home directory.

The bug report format outline consists of several sections. The first section provides information about the machine, operating system, the bash version, and the compilation environment. The second section should be filled in with a description of the bug. The third section should be a description of how to reproduce the bug. The optional fourth section is for a proposed fix. Fixes are encouraged.
Environment
bashbug will utilize the following environment variables if they exist:

EDITOR
    Specifies the preferred editor. If EDITOR is not set, bashbug defaults to emacs. 
HOME
    Directory in which the failed bug report is saved if the mail fails. 
TMPDIR
    Directory in which to create temporary files and directories.

See Also

bash(1)

Authors
Brian Fox, Free Software Foundation
bfox@gnu.org

Chet Ramey, Case Western Reserve University
chet@po.cwru.edu
Referenced By
octave-bug(1) 
