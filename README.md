# MetaFlac

MetaFlac is a library for reading flac meta data with python

    from metaflac import MetaFlac
    metaflac = MetaFlac('/some/music.flac')
    print metaflac.get_streaminfo()
    print metaflac.get_application()
    print metaflac.get_seektable()
    print metaflac.get_picture()
    print metaflac.get_vorbis_comment()
