load('//sys/src/FLAGS', "LIB_COMPILER_FLAGS", "CMD_LINK_OPTS")

cc_binary(
    name="zenith",
    copts=LIB_COMPILER_FLAGS,
    includes=[
        "//sys/include",
        "//amd64/include",
    ],
    deps=[
        "//sys/src/libcomplete:libcomplete",
        "//sys/src/libframe:libframe",
        "//sys/src/libdraw:libdraw",
        "//sys/src/libplumb:libplumb",
        "//sys/src/libthread:libthread",
        "//sys/src/libbio:libbio",
        "//sys/src/libc:libc"
    ],
    srcs=[
        "acme.c",
        "addr.c",
        "buff.c",
        "cols.c",
        "disk.c",
        "ecmd.c",
        "edit.c",
        "elog.c",
        "exec.c",
        "file.c",
        "fsys.c",
        "look.c",
        "regx.c",
        "rows.c",
        "scrl.c",
        "text.c",
        "time.c",
        "util.c",
        "wind.c",
        "xfid.c"
    ],
    linkopts=CMD_LINK_OPTS
)
