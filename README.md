# ZomeWorks

A Unified Graph Data Suite

ZomeWorks is a planned set of software tools designed to work with graph-like knowledge bases in an integrated and seamless way. The suite aims to provide a powerful and flexible solution for managing, navigating, and analyzing complex knowledge networks. The following components are currently planned:

## The (rhi)Zome

A universal data structure for graph data that features:

-   Connection weighting
-   Semantic connection types
-   Rich tagging functionality
-   Built-in set operations
-   Persistence via TerminusDB or similar

The core data structure is maintained in the [zome-core](https://github.com/jaysen/zome-core) repository. Refer to its README for detailed information on usage, installation, and contributing.

## MultiZome

A structure that houses multiple Zomes, equipped with a library of tools to connect to, traverse, mine, and work with multiple external graph-like knowledge/data sources or internal Zomes seamlessly. This component leverages the Zome's metaphors and features to provide a unified experience across various data sources, such as:

-   Knowledge graphs
-   Personal and community wikis
-   Personal and community bookmarks
-   Personal and community tag repositories
-   Social networks
-   The web

## ZomeStool

A desktop application designed for mining, searching, and browsing Zomes and MultiZomes in a coherent and user-friendly manner.

## ZomeWeb

A browser extension that provides a sidewiki-like experience for web annotation and interaction with Zomes or MultiZomes, enabling users to engage with graph-like knowledge bases directly from their web browsers.

Stay tuned for updates on the development progress.
