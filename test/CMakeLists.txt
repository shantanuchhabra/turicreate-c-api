project(TuriTest)

enable_testing()

subdirs(
        capi
        toolkits
        ml_data
        optimization
        user_pagefault
        util
        serialization
        logger
        timer
        random
        # fault
        nanosockets
        fileio
        shmipc
        cppipc
        flexible_type
        parallel
        fiber
        lambda
        sframe
        sgraph
        lazy_eval
        sframe_query_engine
        unity
        sketches
        generics
        table_printer
        network
        process
  )
